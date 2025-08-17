Smart Café Billing System.

📌 Project Definition

Title: Smart Café Billing System
Objective:
A JavaScript-based console + web page application for managing café orders, calculating bills, applying discounts, changing passwords, and generating reports — using only variables, if-else statements, and do…while loops (no arrays, no functions).


---

🧩 Project Tasks

1. 🍽 Place Order System

Input: Customer chooses items from menu:

Coffee – ₹50

Tea – ₹30

Sandwich – ₹80

Pastry – ₹100


Logic:

Loop until user chooses 0.

Track:

Total bill amount

Total items sold

Highest priced item ordered

Lowest priced item ordered



Example Output:

You ordered Coffee. Price: ₹50
Current Total: ₹130


---

2. 🧾 View Bill

Logic:

Subtotal = sum of items

GST = 5% of subtotal

Grand Total = Subtotal + GST


Example Output:

Subtotal: ₹500
GST (5%): ₹25
Grand Total: ₹525


---

3. 💰 Apply Discount

Logic:

If subtotal > ₹1000 → 20% discount

If subtotal > ₹500 → 10% discount

Else → No discount


Example Output:

Original: ₹1200
Discount: ₹240
Final: ₹960


---

4. 🔐 Change Café Password

Logic:

Default password: 1234

If old password matches → update to new password

Else → show error


Example Output:

Password changed successfully.
OR
Incorrect old password.


---

5. 📊 View Café Report

Logic:

Show:

Total items sold

Highest price item

Lowest price item

Average price of items sold



Example Output:

Total Items Sold: 7
Highest Price Item: ₹100
Lowest Price Item: ₹30
Average Price: ₹65


