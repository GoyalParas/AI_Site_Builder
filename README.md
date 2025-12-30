# 🚀 Site Builder

<h1 align="center">
  🔴 <a href="https://ai-site-builder-zomm.vercel.app/" style="color:blue; text-decoration:none;">
    LIVE Link — CLICK HERE 🚀
  </a>
</h1>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?logo=node.js&logoColor=white)](https://nodejs.org/)
[![Prisma](https://img.shields.io/badge/Prisma-3982CE?logo=Prisma&logoColor=white)](https://www.prisma.io/)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)](https://openai.com/)

Transform your creative ideas into stunning, fully functional websites with the power of AI! **Site Builder** is an innovative platform that leverages OpenAI's advanced language models to generate complete websites from simple text descriptions.

## ✨ Features

- **🤖 AI-Powered Generation**: Describe your website in plain English and watch it come to life
- **🔄 Real-Time Preview**: See your website evolve as you refine your prompts
- **👤 User Authentication**: Secure login system with Better Auth
- **📁 Project Management**: Organize and version your website projects
- **💬 Conversational AI**: Chat with the AI to iteratively improve your website
- **🌐 Community Hub**: Share and discover amazing websites created by the community
- **💳 Payment Integration**: Seamless Stripe integration for premium features
- **📱 Responsive Design**: Mobile-first approach ensures great experience on all devices
- **🎨 Modern UI**: Beautiful interface built with React and Tailwind CSS

## 🛠️ Tech Stack

### Frontend
- **React 19** - Modern React with hooks and concurrent features
- **TypeScript** - Type-safe JavaScript
- **Vite** - Fast build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework
- **React Router** - Client-side routing
- **Axios** - HTTP client for API calls
- **Lucide React** - Beautiful icons
- **Better Auth UI** - Authentication components

### Backend
- **Node.js** - JavaScript runtime
- **Express** - Web framework
- **TypeScript** - Type-safe server code
- **Prisma** - Next-generation ORM for PostgreSQL
- **PostgreSQL** - Robust relational database
- **OpenAI API** - AI-powered content generation
- **Stripe** - Payment processing
- **Better Auth** - Authentication library

## 🚀 Quick Start

### Prerequisites
- Node.js (v18 or higher)
- PostgreSQL database
- OpenAI API key
- Stripe account (for payments)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/prompt-to-website.git
   cd prompt-to-website
   ```

2. **Install dependencies**
   ```bash
   # Install client dependencies
   cd client
   npm install

   # Install server dependencies
   cd ../server
   npm install
   ```

3. **Set up the database**
   ```bash
   # Generate Prisma client
   npx prisma generate

   # Run database migrations
   npx prisma migrate dev
   ```

4. **Configure environment variables**

   Create `.env` files in both `client` and `server` directories:

   **server/.env**
   ```env
   DATABASE_URL="postgresql://username:password@localhost:5432/prompt_to_website"
   OPENAI_API_KEY="your_openai_api_key"
   STRIPE_SECRET_KEY="your_stripe_secret_key"
   STRIPE_WEBHOOK_SECRET="your_stripe_webhook_secret"
   BETTER_AUTH_SECRET="your_better_auth_secret"
   ```

   **client/.env**
   ```env
   VITE_API_URL="http://localhost:3001"
   VITE_STRIPE_PUBLISHABLE_KEY="your_stripe_publishable_key"
   ```

5. **Start the development servers**
   ```bash
   # Start the server (from server directory)
   npm run server

   # Start the client (from client directory)
   npm run dev
   ```

6. **Open your browser**

   Navigate to `http://localhost:5173` to start creating websites!

## 📖 Usage

1. **Sign Up/Login**: Create an account or log in to access the platform
2. **Create a Project**: Click "New Project" and enter a descriptive prompt
3. **Watch Magic Happen**: The AI generates your initial website structure
4. **Iterate & Refine**: Use the chat interface to make improvements
5. **Preview & Publish**: View your website and publish when ready
6. **Share with Community**: Showcase your creations in the community section

## 🏗️ Project Structure

```
prompt-to-website/
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Application pages
│   │   ├── lib/            # Utilities and configurations
│   │   └── types/          # TypeScript type definitions
│   ├── public/             # Static assets
│   └── package.json
├── server/                 # Express backend
│   ├── controllers/        # Route controllers
│   ├── lib/                # Database and utilities
│   ├── middlewares/        # Express middlewares
│   ├── routes/             # API routes
│   ├── prisma/             # Database schema and migrations
│   └── package.json
└── README.md
```

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [OpenAI](https://openai.com/) for their incredible language models
- [Prisma](https://www.prisma.io/) for the amazing ORM
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [React](https://reactjs.org/) for the powerful frontend library

---

Made with ❤️ and lots of ☕ by Paras Goyal