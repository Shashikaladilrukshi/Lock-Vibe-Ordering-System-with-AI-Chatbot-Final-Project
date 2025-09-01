🔐 Lock Vibe Ordering System with AI Chatbot

An e-commerce platform for door lock retail built with the MERN stack, integrated with an AI-powered chatbot for real-time customer support. The system enables customers to browse products, place secure orders, and track purchases, while admins can manage inventory, suppliers, and orders from a dashboard.

🚀 Features

🛒 Product catalog browsing & secure ordering

🤖 AI chatbot for instant customer support (inquiries, order status, stock availability)

💳 Stripe payment integration

📧 Automated email notifications with Nodemailer

📦 Real-time inventory, supplier, and order management (Admin Dashboard)

📱 User-friendly, responsive design

🛠 Tech Stack

Frontend: React.js

Backend: Node.js + Express.js

Database: MongoDB

Chatbot: Dialogflow / Rule-based AI

Payments: Stripe

Email Service: Nodemailer

Deployment: Heroku / Optional custom domain

📂 Project Structure
/client   -> React frontend  
/server   -> Node.js + Express backend  
/models   -> MongoDB schemas  
/routes   -> API endpoints  

⚡ Installation & Setup

Clone the repository

git clone https://github.com/your-username/lock-vibe-ordering-system.git
cd lock-vibe-ordering-system


Install dependencies

For backend:

cd server
npm install


For frontend:

cd client
npm install


Set up environment variables
Create a .env file in the server directory:

MONGO_URI=your_mongo_connection_string  
STRIPE_SECRET_KEY=your_stripe_key  
EMAIL_USER=your_email  
EMAIL_PASS=your_password  


Run the app

Start backend:

npm run dev


Start frontend:

npm start

🎯 Deliverables

Functional MERN-based e-commerce platform

AI chatbot for customer support

Stripe-based payment system

Nodemailer automated emails

GitHub-hosted codebase + project report

📌 Future Enhancements

Advanced AI chatbot with NLP

Improved scalability with microservices

Mobile app version (React Native)

Role-based authentication & analytics
