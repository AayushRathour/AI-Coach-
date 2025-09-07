# 🚀 AI Career Coach

> An intelligent career development platform powered by AI to help advance your professional journey.
> https://aicoachgeneratorvaibhav-xzi4.vercel.app/ click this link to go to project

<!-- Deployment Fix: Updated DATABASE_URL with complete Neon connection string -->

## ✨ Features

🤖 **AI-Powered Resume Builder** - Create professional resumes with intelligent suggestions  
📝 **Smart Cover Letter Generator** - Generate personalized cover letters for any job  
🎤 **Interview Practice** - Practice with AI-generated questions and get feedback  
📊 **Career Dashboard** - Track your progress and career insights  
🔐 **Secure Authentication** - User management with Clerk  
📱 **Responsive Design** - Works seamlessly on all devices  

## 🛠 Tech Stack

- **Frontend:** Next.js 15, React, Tailwind CSS, Shadcn UI
- **Backend:** Next.js API Routes, Server Actions
- **Database:** PostgreSQL (Neon) with Prisma ORM
- **Authentication:** Clerk
- **AI:** Google Gemini API
- **Deployment:** Vercel

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/vaibhav-anand-rns/AI-Coach-Generator.git
   cd AI-Coach-Generator
   ```

2. **Install dependencies**
   ```bash
   npm install --legacy-peer-deps
   ```

3. **Environment Setup**
   
   Create a `.env` file in the root directory:
   ```env
   # Database (Neon PostgreSQL)
   DATABASE_URL=your_neon_database_url
   
   # Clerk Authentication
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
   
   # Google Gemini AI
   GEMINI_API_KEY=your_gemini_api_key
   ```

4. **Database Setup**
   ```bash
   npx prisma generate
   npx prisma db push
   ```

5. **Start Development Server**
   ```bash
   npm run dev
   ```

   

## 📖 Documentation

- � **[Complete Beginner's Guide](./COMPLETE_BEGINNER_GUIDE.md)** - Step-by-step setup for beginners
- 🤖 **[AI Assistant Guide](./COPILOT_INSTRUCTION_GUIDE.md)** - Instructions for AI helpers
- 🚀 **[Setup Guide](./SETUP_GUIDE.md)** - Quick setup for developers

## 🔑 API Keys Setup

### Neon Database
1. Create account at [Neon Console](https://console.neon.tech/)
2. Create new project
3. Copy connection string

### Clerk Authentication  
1. Create account at [Clerk Dashboard](https://dashboard.clerk.com/)
2. Create new application
3. Copy API keys from dashboard

### Google Gemini AI
1. Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Create API key
3. Copy the generated key

## 📁 Project Structure

```
├── app/                    # Next.js App Router
│   ├── (auth)/            # Authentication pages
│   ├── (main)/            # Main application
│   └── api/               # API endpoints
├── components/            # Reusable components
├── actions/              # Server actions
├── lib/                  # Utilities
├── prisma/               # Database schema
└── public/               # Static assets
```

## 🎯 Available Commands

```bash
npm run dev          # Start development server
npm run build        # Build for production
npm start           # Start production server
npm run lint        # Run ESLint
npx prisma studio   # Open database GUI
```

## 🌐 Deployment

Deploy to Vercel with one click:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vaibhav-anand-rns/AI-Coach-Generator)

### Manual Deployment
1. Push to GitHub
2. Connect to Vercel
3. Add environment variables
4. Deploy

## 🤝 Contributing

1. Fork the project
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open Pull Request

## 📄 License

This project is licensed under the MIT License.

---



For support or questions, check the documentation or open an issue!
