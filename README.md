# Student Expense Tracker (Expo + React Native + SQLite)

A simple mobile application that helps students track their daily expenses. The app is built with **React Native**, **Expo**, and **SQLite**, and stores all data locally on the device. Users can add, view, edit, search, and filter expenses through a clean and easy-to-use interface.

---

## 🚀 How to Run the App

Follow these steps to run the project using Expo Go.

### 1. Install dependencies
Run this inside the project directory:
`npm install`

### 2. Start the development server
Use the standard Expo command:
`npx expo start`

If needed for some networks, you can also use:
`npx expo start --tunnel`

### 3. Open the app on your mobile device
1. Install **Expo Go** from the App Store or Google Play  
2. Scan the QR code shown in your terminal or browser  
3. The app will load automatically on your device  

---

## 📱 Features

### **Add New Expenses**  
Quickly record an expense by entering the amount, category, optional note, and date. All entries are saved locally in SQLite and remain available even after restarting the app.

### **View Expense List**  
Browse all expenses in a clean, organized list with the newest entries shown first. Each item displays the amount, category, date, and optional note.

### **Edit Existing Expenses**  
Tap the “Edit” button next to any expense to update its amount, category, note, or date. Changes save instantly using SQLite and the list updates immediately.

### **Delete Expenses**  
Remove any saved expense with a single tap using the built-in delete button.

### **Date-Based Filtering**  
Quickly filter expenses by:
- All  
- This Week  
- This Month  
Filtering updates both the list and the totals instantly.

### **Total Spending Display**  
See your total spending based on the active filter. The total updates automatically as new expenses are added, edited, or removed.

### **Category Breakdown**  
View a simple summary of spending by category for the selected filter. This makes it easy to spot patterns in your spending.

### **Search Bar**  
Search through your expenses by category, amount, or note text. The search feature works seamlessly alongside date filters and updates instantly.

### **Persistent Local Data**  
All information is stored in SQLite and remains available after closing and reopening the app.
