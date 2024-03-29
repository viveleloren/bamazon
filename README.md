# Project Title

# BAMAZON

---

- **For:** University of California Davis Coding Bootcamp
- **Developer:** Loren Brown
- **Deployment Date** 06/08/2019
- **Built With** Node.js, MySQL

### Description & Requirements

---

OVERVIEW

This application is formatted to take a Database identical to the original instructions. It takes a database named Bamazon, a table named Products, and the columns of ItemID, ProductName, DepartmentName, Price, and StockQuantity.

- This application is the Basic application. Formatted exactly like the original file names of BamazonCustomer.js

---

- Upon running the program, the user will be shown all of the inventory in the database, and will be asked to give the ID of the product they would like to purchase:                
 
  ![screen](https://user-images.githubusercontent.com/47464812/59154884-40ff1400-8a31-11e9-9266-c1f45e1aecec.jpeg)
 
- Once the user gives the ID of the product, they are asked how many units of the product they would like to buy. Once they enter the amount, if the number that they entered is less than or equal to the current inventory number for the selected product, then the inputted number is subtracted from the product's available quantity and the product's new quantity is updated in the MySQL database. The user is shown a message stating that the products have been bought along with the total cost of their transaction. They are then asked whether they would like to shop again.

![screen(2)](https://user-images.githubusercontent.com/47464812/59154931-76f0c800-8a32-11e9-9bb5-e3b4fb2d6d85.jpeg)

---

- If the user types in a quantity that is larger than the current available quantity for the product that they have chosen, then an error message pops up, and they are taken back to the starting prompt.

---

![screen(3)](https://user-images.githubusercontent.com/47464812/59154948-b6b7af80-8a32-11e9-8d31-85d499aefce4.png)

Coded and Compiled by Loren Brown


