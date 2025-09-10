🛒 Python Mini E-commerce App

A simple command-line E-commerce simulation built in Python, demonstrating how core data structures (List, Tuple, Set, Dictionary) can be applied to a real-world scenario.

✨ Features

✅ Show products available in store
✅ Add/remove items from cart
✅ View cart with total amount
✅ Checkout with a bill receipt
✅ Track unique buyers across sessions

🧠 Concepts Used

Dictionary → Product database (product_id → (name, price))

Tuple → Immutable product details

List → Shopping cart

Set → Unique buyers

📂 Project Structure
📦 mini-ecommerce-app
 ┣ 📜 ecommerce_app.py   # Main script
 ┗ 📜 README.md          # Documentation

▶️ Run Locally

Clone the repository

git clone <your-repo-link>
cd mini-ecommerce-app


Run the app

python ecommerce_app.py


Follow the menu to shop 👇

👋 Welcome to Python E-commerce App!
Enter your name: Alex

========= MENU =========
1. Show Products
2. Add to Cart
3. Remove from Cart
4. View Cart
5. Checkout
6. Exit

📸 Demo (Sample Output)
Available Products:
ID: 101, Name: Laptop, Price: ₹50000
ID: 102, Name: Mouse, Price: ₹800
ID: 103, Name: Keyboard, Price: ₹1500
ID: 104, Name: Monitor, Price: ₹10000
ID: 105, Name: Headphones, Price: ₹2000

✅ Mouse added to cart!
🗑️ Keyboard removed from cart!
Total: ₹50800

🚀 Future Improvements

Add product quantities

Save user order history

Discount/coupon system

User authentication

🙌 Acknowledgement

This project was built as a learning-by-doing exercise to apply Python fundamentals in a practical way.
