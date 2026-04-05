# 🌾 Revolutionizing Agriculture with AgriEdge Or-Mange Ltd  
**A Salesforce-Driven Order Management System (OMS)**  

This project is a Salesforce CRM-based custom Order Management System designed for **AgriEdge Or-Mange Ltd**, a leader in the agriculture and food production industry. The system is tailored to manage orders, automate processing, streamline inventory tracking, and enhance customer service experiences.

---

## 📘 Overview  
AgriEdge handles a wide variety of agricultural products like seeds, fertilizers, harvested crops, and processed food items. This project addresses challenges such as:

- Manual order entry errors  
- Lack of real-time inventory visibility  
- Disconnected customer service channels  

The solution uses Salesforce's capabilities to provide a **robust, automated, and scalable OMS**, enhancing operational efficiency and customer satisfaction.

---

## 🎯 Key Features  
✅ Automated Order Creation and Status Updates  
✅ Real-Time Inventory Tracking  
✅ Customer Notifications via Email  
✅ Task Creation for Follow-ups  
✅ Product-Order Relationship via Junction Object  
✅ Role-based Access and Security  
✅ Reports & Dashboards for Order Insights  
✅ Scalable for shipment and delivery modules

---

## 🧰 Technologies Used  
- Salesforce CRM (Developer Edition)  
- Apex (Class, Triggers, Test Classes)  
- Flow Automation (Record-Triggered Flows)  
- Process Builder  
- Validation Rules  
- Profile, Role, and User Management  
- Report & Dashboard Builder  

---

## 🧱 Data Model  
### 🔹 Custom Objects  
- **AgriEdge Order**  
  - Fields: Order Number (Auto), Order Date, Status, Total Amount, Payment Status, Shipping Address  
- **AgriEdge Product**  
  - Fields: Name, Unit Price, Description  
- **AgriEdge OrderItem (Junction Object)**  
  - Links Orders with Products  
  - Fields: Quantity, Unit Price, Total

### 🔹 Standard Objects Used  
- **Account** – For Customer Info  
- **User** – For Sales Reps/Admins

---

## ⚙️ Automation Implemented  
- **Apex Trigger**:  
  - Auto-calculate OrderItem total  
  - Update Order total based on items  
- **Apex Class**:  
  - Handles business logic and reusable methods  
- **Flows**:  
  - Send Email Notification on Order Status Change  
  - Create Task when new Order is created  
- **Validation Rules**:  
  - Prevent negative quantities  
  - Ensure mandatory fields before saving  

---

## 📈 Reports & Dashboards  
- Order Summary Report  
- Product-wise Sales Report  
- Dashboard for Sales Manager View  

---

## 🔐 Security  
- Role Hierarchy for Sales Rep and Manager  
- Profile-based Field-Level Security  
- Record-Level Sharing Rules  

---

## 🔮 Future Enhancements  
- 📦 Shipment Tracking  
- 📧 SMS/Email Alerts for Delivery Updates  
- 📱 Salesforce Mobile App Integration  
- 🧾 Invoice Generation  
- 🗃️ Archival of Completed Orders  
- 📊 Predictive Analytics for Demand Forecasting  

---

## 🧑‍💻 Author  
**Mulapaka Sudharshan Reddy**  
Final Year B.Tech (CSE) Student  
K.S.R.M COLLEGE OF ENGINEERING  
📧 Email: sudharshanr379@gmail.com  
🔗 GitHub: [github.com/SudharshanMulapaka](https://github.com/SudharshanMulapaka)

---

## 📄 License  
This project is intended for academic and educational purposes only.
