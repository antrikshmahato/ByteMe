Byte Me Canteen System – Overview

Byte Me Canteen System is a Java-based CLI + GUI application designed to efficiently manage food ordering operations in a college canteen. The system supports role-based access for both customers and admins, enabling smooth management of menu items, orders, reviews, and daily sales.
The project includes a fully integrated GUI, robust backend logic, and comprehensive unit testing.

✨ Features
Admin Features

Menu Management:
Add, update, and delete menu items.

Order Management:
View pending orders, update order status, process refunds, and handle special requests.

Daily Sales Report:
Generate detailed sales reports, including:

Total revenue

Most popular items

Total number of orders

Customer Features

Food Ordering:
Add, update, or remove items from the cart and proceed to checkout using cash or card.

Reordering:
Quickly reorder previous meals from order history.

Reviews:
Submit reviews for food items and view feedback from other customers.

🖥 Graphical User Interface

The project includes a user-friendly GUI for:

Menu browsing and ordering

Viewing and managing order history

Admin-level menu and order management

Both customers and admins can operate core functionalities through the GUI, enhancing accessibility and usability.

⌨️ Command-Line Interface

A full CLI mode is available for users who prefer terminal-based interaction. All core operations for both roles are supported.

🧪 Testing

Comprehensive unit tests ensure system reliability and correctness. Key test cases include:

Unavailable Items in Cart:
Ensures that items not present in the menu cannot be added or ordered.

Invalid Login Attempts:
Verifies that invalid usernames and passwords are rejected to prevent unauthorized access.

Additional tests cover ordering logic, menu updates, and more.

📊 UML Diagram

A detailed UML diagram is included to illustrate system architecture, class relationships, and workflow logic.
