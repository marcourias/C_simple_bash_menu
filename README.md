# Beverage Inventory Management System

This code implements a simple beverage inventory management system. It uses C programming language and consists of structures to store data related to beverages and waste. The program provides a menu-driven interface for performing various operations such as registering sales, displaying stock levels, calculating income from sales, recording beverage waste, and showing the economic loss due to waste.

## Explanation

The code begins by including necessary header files, defining structures for storing beverage and waste data, and declaring a function for clearing the screen.

Next, there is a function `inicializarMermas` to initialize the waste data.

In the `main` function, an array of `Refresco` structures is defined to store beverage data. Each structure contains information such as the name of the beverage, the quantity in stock, and the number of sales.

Another array of `Merma` structures is defined to store waste data. Each structure represents a type of beverage and includes information such as the name, cost, and total economic loss due to waste.

The program then obtains the current date and time using the `time` function.

A `while` loop is used to display the main menu and perform operations based on user input. The menu options include registering sales, displaying stock levels, showing sales data, calculating income from sales, recording beverage waste, showing economic loss due to waste, and exiting the program.

Based on the user's selection, different functions are called to perform the corresponding operations. These functions interact with the user, update data structures, and display relevant information.

The program continues to run until the user selects the option to exit.

## Conclusion

This code provides a basic implementation of a beverage inventory management system. It allows for tracking stock levels, sales, income, and waste, providing an overview of beverage operations. It can be further extended and enhanced to meet specific requirements and integrate with other systems.

