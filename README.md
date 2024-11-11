SQLite Database: The init_db function creates an SQLite database with two tables: users for authentication and inventory for storing product details. We use sqlite3 to interact with the database.
User Authentication: Functions create_user and verify_user handle user account creation and login verification. Passwords are hashed using bcrypt for security.
Inventory Management: The program allows users to add, edit, delete, and list products. The functions add_product, edit_product, delete_product, and get_inventory manage the inventory items.
Low Stock Alert: The function low_stock_alert checks inventory and alerts users when products are below a certain threshold.
TKINTER GUI: The InventoryApp class uses Tkinter for the graphical interface, including login, product management, and inventory list displays.
INSTALL PIP

#FEATURES TO ADD UP :----
Sales tracking and summaries.
Better error handling and input validation.
Export data to CSV or PDF.
TESTING OF BUGS BY SLELENIUM & AUTOMATION.
Devop and devour the app.
