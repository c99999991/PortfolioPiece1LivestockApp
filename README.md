# PortfolioPiece1LivestockApp

This repositor contains a demonstration of the forcast page from Task 4 of COMP609 Application Development.
The requirements of this task were to develop an application using C# and .NET MAUI and implementing a SQLite database.

The purpose of this livestock management application is to provide farmers with tools to efficiently monitor and track, 
livestock and the produce such as wool and milk.

This is the GUI of the Forcast page. It allows the user to add generic or custom livestock to a virtual collection, and 
providing dynamic calculations for the totals of Cost, Produce, Tax, Income and Profit.
![forcast1](https://github.com/c99999991/PortfolioPiece1LivestockApp/assets/142708292/acda3a4b-3a56-41a6-849c-d12f8bc2199a)

The [Add average] form allows the user to input any quantity of the average of the selected livestock variant.
The average is taken from the average of that animal type from within the existing stock so any lavistock added 
in this page will not affect this average.

This is the event handler which is called by the button when clicked by th user:
![AddAve](https://github.com/c99999991/PortfolioPiece1LivestockApp/assets/142708292/0b833716-d796-4072-a737-a443bf16c97d)
Which calls this public method in the View Model of the page if the input is determined to be valid:
![AddAveVM](https://github.com/c99999991/PortfolioPiece1LivestockApp/assets/142708292/1cceb5cf-7e00-4664-a73a-ab8ee9d62d85)

