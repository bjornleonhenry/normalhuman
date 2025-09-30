# AI-Powered Email Client

A comprehensive full-stack email client application with AI integration, featuring modern web technologies and subscription management.

## Features

- 🤖 AI-powered email processing and analysis
- 💳 Subscription management with Stripe integration
- 🔐 Secure authentication with Clerk
- 📧 Advanced email management and organization
- 📊 Analytics and insights dashboard
- 🌐 Modern responsive web interface

## Tech Stack

- **Next.js** - React framework with App Router
- **React** - Frontend library
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first styling
- **Clerk** - Authentication and user management
- **Prisma ORM** - Database management
- **PostgreSQL** - Relational database
- **AWS SDK** - Cloud storage integration
- **OpenAI API** - AI functionality
- **Stripe** - Payment processing
- **Pinecone** - Vector database for AI features
- **TanStack Query** - Data fetching and caching

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn or pnpm

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd normalhuman
```

2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Set up environment variables by creating a `.env.local` file with your API keys and configuration

4. Start the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

5. Open your browser and navigate to `http://localhost:3000`

## Building for Production

```bash
npm run build
# or
yarn build
# or
pnpm build
```

## Deployment

The application can be deployed to Vercel, Netlify, or any other hosting platform that supports Next.js applications.
