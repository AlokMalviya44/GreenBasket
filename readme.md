🛒 Green Basket — E-commerce Web Application
Green Basket is a modern, full-stack e-commerce web application built with React (Vite), Node.js, Express, MongoDB, and Stripe for payment processing. It allows customers to browse products, manage carts, securely authenticate, and make payments with ease.

🔧 Tech Stack
Frontend: React (Vite), Tailwind CSS, Axios
Backend: Node.js, Express.js
Database: MongoDB Atlas
Authentication: JSON Web Tokens (JWT), bcrypt
Media Storage: Cloudinary
Payments: Stripe

🚀 Features
1. User & Admin authentication (JWT)
2. Product listing, cart, and order management
Admin dashboard for product upload
Image upload via Cloudinary
Stripe integration for payment
Responsive design with modern UI
Also to use seller features just add /seller in url

🛠️ Installation & Setup

1. Clone the Repository
git clone https://github.com/your-username/green-basket.git
cd green-basket

2. Setup Backend
cd backend
npm install

->Rename .env.example to .env and fill in your values.
->Start the backend server: npm start

3. Setup Frontend

cd ../frontend
npm install
npm run dev
