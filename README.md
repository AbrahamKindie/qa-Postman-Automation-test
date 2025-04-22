# 📬 Contact Us & 🔔 Notifications API – Postman Test Scripts

This repository contains API test collections for the **Contact Us** and **Notifications** modules of a web application.
The tests are created and exported from Postman, covering both **positive** and **negative** scenarios including **authorization handling**.


---
## 📁 Project Structure
---

## 🧪 What's Tested

### 🔔 Notifications API Tests
- **GET All Notifications** – Ensure the system retrieves all notifications correctly for the logged-in user.
- **POST Notification** – Create a new notification with valid data.
- **Mark as Read** – Update notification status to `read`.
- **Enable/Disable Settings** – Toggle notification preferences.
- **Authorization Check** – Ensure protected endpoints return appropriate errors when called without valid tokens.

### 📬 Contact Us API Tests
- **POST Feedback** – Submit feedback using the contact form.
- **GET Feedback** – Retrieve feedback entries with all expected properties.
- **Authorization Check** – Ensure only authorized users can access sensitive data.

---

## 🚀 How to Run the Tests

### 📌 Using Postman
1. Open **Postman**
2. Go to **File > Import**
3. Select the `.postman_collection.json` files inside `/collections`
4. Import the environment file from `/environments`
5. Choose the environment in the top-right dropdown
6. Run the collections via **Collection Runner**


🛡️ Authorization Notes
These collections include tests that require:

Bearer Token authentication

Make sure to set your token in the Authorization tab or as a variable in your environment



