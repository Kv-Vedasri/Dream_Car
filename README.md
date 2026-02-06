# 🚗 Full-Stack AI Car Marketplace

A modern **full-stack AI-powered car marketplace** built with **Next.js**, **Supabase**, **Prisma**, **Tailwind CSS**, **Shadcn UI**, **Clerk Authentication**, **ArcJet security**, and **Google Gemini AI**.

This platform allows users to explore cars, save favorites, book test drives, and enables admins to manage listings through a secure dashboard.

---

## ✨ Features

- 🔐 Authentication with **Clerk**
- 🚘 Car listings with images and filters
- 💾 Save favorite cars
- 📅 Book test drives
- 🧠 AI-powered features using **Google Gemini**
- 🛠 Admin dashboard for car management
- 🎨 Modern UI with **Tailwind CSS & Shadcn UI**
- 🛡 Security & rate limiting using **ArcJet**
- 🗄 Database management with **Prisma + Supabase**

---

## 🛠 Tech Stack

- **Frontend:** Next.js (App Router), Tailwind CSS, Shadcn UI  
- **Backend:** Next.js Server Actions  
- **Database:** Supabase (PostgreSQL)  
- **ORM:** Prisma  
- **Authentication:** Clerk  
- **AI:** Google Gemini API  
- **Security:** ArcJet  

---

## 📁 Project Structure

app/ # Next.js App Router
components/ # Reusable UI components
actions/ # Server actions
prisma/ # Prisma schema & migrations
public/ # Static assets
lib/ # Utilities & helpers
middleware.js # Middleware logic
package.json


---

## ⚙️ Environment Variables

Create a `.env` file in the root of the project and add the following:

```env
# Database
DATABASE_URL=
DIRECT_URL=

# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

# AI (Google Gemini)
GEMINI_API_KEY=

# Security (ArcJet)
ARCJET_KEY=

🚀 Getting Started
1. Clone the repository
git clone https://github.com/Kv-Vedasri/Dream_Car.git
cd Dream_Car

2. Install dependencies
npm install
# or
pnpm install

3. Setup Prisma
npx prisma generate
npx prisma migrate deploy

4. Run the development server
npm run dev
# or
pnpm dev


Open http://localhost:3000
 in your browser.

🧪 Scripts
npm run dev       # Start development server
npm run build     # Build for production
npm run start     # Start production server

📌 Future Improvements

Payment integration

AI car price prediction

User reviews & ratings

Advanced admin analytics

Deployment (Vercel)

🤝 Contributing

Contributions are welcome.
Fork the repository and submit a pull request.

📄 License

This project is licensed under the MIT License.

👩‍💻 Author

Vedasri Varsha
GitHub: Kv-Vedasri
