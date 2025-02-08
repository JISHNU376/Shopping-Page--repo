# Shopping Page (Java Console Application)

## Overview
This is a simple Java-based console application that simulates an **Online Shopping Page**. Users can browse products, add/remove items from their cart, and proceed to checkout with a simulated payment process.

## Features
- View available products with names and prices
- Add products to the shopping cart
- Remove products from the shopping cart
- View the shopping cart with the total price
- Checkout and simulate payment
- User-friendly menu-driven console interface

## Technologies Used
- Java (Core Java)
- Collections Framework (ArrayList)
- Scanner class for user input handling

## How to Run
1. Clone or download this repository.
2. Open the project in any Java-supported IDE (e.g., IntelliJ IDEA, Eclipse, VS Code).
3. Compile and run the `ShoppingPage.java` file.
4. Follow the console prompts to interact with the shopping page.

## Usage Guide
When you run the program, you will see the following menu:
```
--- Shopping Page ---
1. View Products
2. Add Product to Cart
3. Remove Product from Cart
4. View Cart
5. Checkout
6. Exit
```
### Example Workflow:
1. Select **1** to view available products.
2. Select **2** and enter a product number to add it to the cart.
3. Select **4** to view the cart contents.
4. Select **5** to checkout and simulate payment.
5. Select **6** to exit the program.

## Sample Output
```
Available Products:
1. Laptop - ₹75000.0
2. Smartphone - ₹25000.0
3. Headphones - ₹2000.0
4. Keyboard - ₹1500.0

Enter your choice: 2
Enter product number to add to cart: 1
Laptop added to the cart.

Enter your choice: 4
Shopping Cart:
- Laptop - ₹75000.0

Enter your choice: 5
Total amount: ₹75000.0
Payment simulated successfully. Thank you for shopping!
```

## Future Enhancements
- Implement **user authentication** to track multiple users' carts.
- Add **discount codes and promotional offers**.
- Introduce **database storage** for product inventory and user purchases.
- Implement a **graphical user interface (GUI)** for better usability.

