Amazona — E-commerce Web App

A modern Full-Stack E-commerce platform built with Next.js 16, TypeScript, Tailwind CSS, and Turbopack.
It provides a fast, secure, and scalable shopping experience with user authentication, product management, and order tracking.

# Tech Stack

Frontend

Next.js 16 (Turbopack)

React 18

TypeScript

Tailwind CSS

Shadcn/UI
(for reusable UI components)

Backend / API

Next.js API routes (proxying requests)

Axios

External REST API integration (for authentication, products, etc.)

# Authentication

NextAuth.js
with Google OAuth

HttpOnly cookies for secure token management

Database

External API-backed database integrate with MongoDB

# Features

✅ User Authentication (Google & Credentials)
✅ Product Listing, Search, and Pagination
✅ Add to Cart / Checkout Flow
✅ Admin Dashboard for Product & Order Management
✅ Inventory Management
✅ Export Reports (CSV, XLSX, PDF)
✅ Password Reset Flow (OTP-based)
✅ Responsive UI with TailwindCSS
✅ Light & Dark Theme Support

⚙️ Installation & Setup

1. Clone the repository
   git clone https://github.com/fsa-22/amazona.git
   cd amazona

2. Install dependencies
   npm install

3. Configure environment variables
   Create a .env.local file in the root directory:
   NEXTAUTH_URL=http://localhost:3000
   NEXTAUTH_SECRET=your_secret_key

GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

API_BASE_URL=https://your-backend-api.com

4. Run the development server
   npm run dev

Then open:
👉 http://localhost:3000

# Folder Structure

app/
├── api/ # Next.js API routes (proxies backend calls)
├── dashboard/ # Protected admin dashboard pages
├── inventory/ # Inventory management views
├── log-in/ # Auth pages
├── (components)/ # Reusable UI components
├── globals.css # Global styles (Tailwind + theme variables)
└── layout.tsx # Root layout file

lib/
├── services/ # API proxy service functions
├── utils/ # Helper functions (tokens, formatting, etc.)

# Scripts

Command Description
npm run dev Start development server
npm run build Build for production
npm run start Start production server
npm run lint Run lint checks

# Troubleshooting

If you encounter:

Failed to load SWC binary for win32/x64

Run:

npm install --save-dev @next/swc-win32-x64-msvc

# Future Improvements

Integrate Stripe or Paystack payments

Add product reviews & ratings

Add AI-powered recommendations

# Author

Simeon Fowotade
Frontend Developer | Next.js • TypeScript • Tailwind • Nodejs • Express • NonSQL
. LinkedIn
• GitHub
• Portfolio
