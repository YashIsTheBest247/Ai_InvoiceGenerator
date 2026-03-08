🧾 AI Powered Invoice Generator (MERN Stack)
An AI-powered Invoice Generator built using the MERN Stack (MongoDB, Express.js, React.js, Node.js) that allows users to generate professional invoices instantly using AI. The system automates invoice creation, tax calculations, client management, and PDF export.

### 🚀 Features
1. 🔐 User Authentication (Signup/Login with JWT)
2. 🤖 AI-powered invoice description generation
3. 📊 Automatic tax & total calculation
4. 👤 Client management system
5. 📄 Generate & Download Invoice as PDF
6. ☁️ MongoDB database integration
7. 📱 Responsive UI (React + Tailwind/Bootstrap)
8. 🗂 Invoice history tracking
9. 📈 Dashboard with invoice analytics (optional)

🏗 Tech Stack
Frontend
React.js
Axios
React Router
Tailwind CSS / Bootstrap

Backend
Node.js
Express.js
MongoDB (Mongoose ODM)
JWT Authentication
OpenAI API (for AI description generation)

#**Folder Structure**
```bash
ai-invoice-generator/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── components/
│   │   └── App.js
│   └── package.json
│
└── README.md
```
🧠 How AI Works
User enters:
Service/Product Name
Quantity
Price
Optional notes

AI generates:
Professional invoice description
Suggested payment terms
Tax summary (optional logic)

The AI response is processed and stored in MongoDB along with invoice data.

### 🔒 Authentication Flow
User registers with email & password
Password hashed using bcrypt
JWT token generated on login
Protected routes use JWT middleware

### 📄 PDF Generation
Invoices can be exported as PDF using:
jspdf (Frontend)
    or
pdfkit (Backend)
