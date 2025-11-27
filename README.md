# **Expense Management System**

## 🌐 GitHub Repo  
```bash
https://github.com/Prakashsaw/Expense-Management-System
```

## 🚀 Live Demo  
```bash
https://expense-management-system-prakash.netlify.app/
```

## 📌 Description  
The **Expense Management System** is a web-based application designed to help users efficiently track and manage their financial transactions.  
It provides features like user authentication, expense tracking, and data visualization to ensure a seamless budgeting experience.

### 🔹 Key Functionalities:  
- **User Authentication:** Secure login & registration with **email verification**.  
- **Password Security:** **Bcrypt** encryption for passwords and **JWT token-based authentication**.  
- **Password Recovery:** Forgot password functionality with email-based reset link.  
- **Expense Management:** Add, edit, delete, and categorize expenses with filtering options.  
  - **Search Transactions:** Search for specific transactions quickly.  
  - **Export to Excel:** Download filtered expenses with a date-based filename.  
- **Financial Insights:** View expenses **weekly, monthly, yearly**, and through **custom date ranges**.  
- **Data Analytics:** Expense visualization with **charts & graphs**.

---

## 🛠 Tech Stack  

### **Frontend:**  
- React.js, Bootstrap, Ant Design, CSS  

### **Backend:**  
- Node.js, Express.js, Nodemailer

### **Database:**  
- MongoDB  

---

## ⚙️ Run Locally  

### **Step 1: Clone the project**  
```bash
git clone https://github.com/anamikalodhi01/ExpenseWise.git
```

### **Step 2: Navigate to the project directory**  
```bash
cd ExpenseWise
```

### **Step 3: Install dependencies**  

#### Install dependencies for the frontend  
```bash
cd client/
npm install
```

#### Install dependencies for the backend  
```bash
cd server/
npm install
```

### **Step 4: Set up environment variables**  
Create a **.env** file inside the `server/` directory and add the following:  
```bash
MONGO_URL=
PORT=

BCRYPT_SALT=
JWT_SECRETE_KEY=
EXPIRE_IN=

EMAIL_HOST=
EMAIL_PORT=
EMAIL_USER=
EMAIL_PASS=
EMAIL_FROM=

FAST2SMS_API_KEY=
```

### **Step 5: Start the application**  

#### Start the frontend  
```bash
// Open a new terminal
cd client
npm run start
```

#### Start the backend  
```bash
// Open a new terminal
cd server
npm run start
```

### **Step 6: Access the app**  
Once the setup is complete, the app will be running on your local system.  

---

## 🔥 Features

- **🔒 Secure User Authentication:** Register, log in, and log out securely.  
- **📧 Email Verification:** Verify accounts via a confirmation link sent to the email.  
- **🔑 Password Management:** Forgot password functionality with email reset link.  
- **📝 User Profile Management:** Update profile details and change passwords after login.  

- **💰 Transaction Management:**  
  - Add, edit, and delete financial transactions with confirmation prompts.  
  - Categorize transactions into **income** or **expenses**.  
  - **🔍 Search Transactions:** Quickly search for transactions using keywords.  
  - **📤 Export to Excel:** Download filtered transactions as an Excel file with a **date-based filename**.  

- **📊 Financial Overview:**  
  - View transaction history **weekly, monthly, and yearly**.  
  - Filter transactions by **custom date range**.  
  - Filter by **income, expenses, or both**.  

- **📈 Data Analytics:** Interactive **graphs & charts** for expense tracking.


---
