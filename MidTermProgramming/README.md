# Zara-Sykes-ITD-1203-60442-ZS-Class-Projects/MidTermProgramming

Write a C program that creates customers’ bills for a carpet company when the following information is given:

    the length and the width of the carpet in feet

    the carpet price per square foot

    the percent of discount for each customer

The labor cost is fixed at $0.35 per square foot. It is to be defined as a constant. The tax rate is 8.5% applied after the discount. It is also to be defined as a constant. The input data consist of a set of three integers representing the length and width of the room to be carpeted, the percentage of the discount the owner gives to a customer, and a real number representing the unit price of the carpet. The program is to prompt the user for this input as shown here. (Colored numbers are typical responses.)
![Screenshot 2024-10-25 121039](https://github.com/user-attachments/assets/ae663f13-ca0f-4414-8f28-2c9bccb22ce8)


The output is shown here. Be careful to align the decimal points.
![Screenshot 2024-10-25 120757](https://github.com/user-attachments/assets/d12ff7d4-8074-47c5-b42d-762955f17526)

The program’s design should use main and at least the six functions described as follows:

    a. Read data from the keyboard. This function is to use addresses to read all data and place them in the calling function’s variables.

    b. Calculate values. This function calls three subfunctions. Each function is to use addresses to store their results.

       * Calculate the installed price. This function calculates area, carpet cost, labor cost, and installed price. The installed price is the cost of the carpet and the cost of the labor.

       * Calculate the subtotal. This function calculates the discount and subtotal.

       * Calculate the total price with discount and tax. This function calculates the tax and the total price.

    c. Print the result. Use two subfunctions to print the results: one to print the measurements, and one to print the charges.

Test your program with the test data shown in Table 4-3.
![Screenshot 2024-10-25 120652](https://github.com/user-attachments/assets/9e81070c-5c53-4ddf-a9a7-202e061b522b)
