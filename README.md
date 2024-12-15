### Question: Implementing a Shopping Cart System

**Objective**: Design and implement a simple shopping cart system using C++. Your solution should utilize classes and vectors to manage products in the cart.

**Requirements**:

1. **Define a `Product` Class**:
   - The class should have the following attributes:
     - `name`: A string representing the name of the product.
     - `price`: A double representing the price of the product.
   - Include a constructor to initialize these attributes.
   - Implement a method `display()` that prints the product's name and price.

2. **Define a `ShoppingCart` Class**:
   - This class should have a private vector of `Product` objects to store the products in the cart.
   - Implement the following methods:
     - `addProduct(const Product& product)`: Adds a product to the shopping cart.
     - `viewCart() const`: Displays all products currently in the shopping cart.
     - `removeProduct(const std::string& productName)`: Removes a specified product from the cart by its name.
     - `calculateTotal() const`: Calculates and returns the total price of all products in the cart.

3. **Main Function**:
   - Create an instance of `ShoppingCart`.
   - Add at least three different products to the cart using the `addProduct()` method.
   - Display the contents of the cart using `viewCart()`.
   - Calculate and print the total price of items in the cart using `calculateTotal()`.
   - Remove one product from the cart using `removeProduct()`.
   - Display the updated contents of the cart and recalculate the total price.

**Example Output**:
```
Apple has been added to the cart.
Banana has been added to the cart.
Orange has been added to the cart.
Shopping Cart Contents:
Product: Apple, Price: $0.99
Product: Banana, Price: $0.59
Product: Orange, Price: $0.79
Total Price: $2.37
Banana has been removed from the cart.
Shopping Cart Contents:
Product: Apple, Price: $0.99
Product: Orange, Price: $0.79
Total Price after removal: $1.78
```

---
