# Prompt Management Platform

<div align="center">
  <img src="https://github.com/PromptKits/.github/profile/resources/logo.png" alt="Logo" width="200"/>
  
  <p>A comprehensive platform for managing, optimizing, and trading AI prompts with advanced features for both individual users and businesses.</p>

  <div>
    <img src="https://img.shields.io/badge/-React-222222?style=flat&logo=React&logoColor=61DAFB" alt="React"/>
    <img src="https://img.shields.io/badge/-TypeScript-000000?style=flat&logo=typescript" alt="TypeScript"/>
    <img src="https://img.shields.io/badge/-React_Native-000000?style=flat&logo=react" alt="React Native"/>
    <img src="https://img.shields.io/badge/-NestJS-000000?style=flat&logo=nestjs" alt="NestJS"/>
    <img src="https://img.shields.io/badge/-TypeORM-000000?style=flat&logo=typeorm" alt="TypeORM"/>
    <img src="https://img.shields.io/badge/-Firebase-000000?style=flat&logo=firebase" alt="Firebase"/>
    <img src="https://img.shields.io/badge/-OpenAI-000000?style=flat&logo=openai" alt="OpenAI"/>
    <img src="https://img.shields.io/badge/-Stripe-000000?style=flat&logo=stripe" alt="Stripe"/>
  </div>
</div>

## 📋 Table of Contents

- [Prompt Management Platform](#prompt-management-platform)
  - [📋 Table of Contents](#-table-of-contents)
  - [🚀 Overview](#-overview)
  - [✨ Key Features](#-key-features)
    - [🎯 Prompt Management](#-prompt-management)
    - [🤖 AI Optimization](#-ai-optimization)
    - [🛍️ Prompt Marketplace](#️-prompt-marketplace)
    - [📝 Prompt Templates](#-prompt-templates)
    - [💬 Prompt Chat](#-prompt-chat)
  - [🛠️ Technical Stack](#️-technical-stack)
    - [Frontend](#frontend)
    - [Backend](#backend)
  - [💎 Subscription Tiers](#-subscription-tiers)
    - [Free Tier](#free-tier)
    - [Pro Tier](#pro-tier)
  - [🚀 Getting Started](#-getting-started)
  - [⚙️ Environment Variables](#️-environment-variables)
  - [📞 Support](#-support)
  - [📄 License](#-license)

## 🚀 Overview

Our platform provides a complete solution for managing and optimizing AI prompts, featuring a marketplace for buying and selling prompts, AI-powered optimization tools, and customizable templates for various use cases.

## ✨ Key Features

### 🎯 Prompt Management

- Create, read, update, and delete prompts
- Detailed prompt attributes (title, description, category, tags, tone, context)
- Support for output images (DALL·E / Midjourney)
- Visibility controls (Public/Private/Draft)

### 🤖 AI Optimization

- Prompt analysis based on clarity, creativity, and output control
- Quality scoring (AI-generated and user votes)
- AI-powered prompt rewriting suggestions
- Visual prompt analysis

### 🛍️ Prompt Marketplace

- Browse and search prompts by type, tags, and authors
- Detailed prompt previews with images and creator profiles
- Secure payment processing via Stripe
- Rating and review system

### 📝 Prompt Templates

- Industry-specific templates:
  - Marketing (email, caption, ad copy)
  - Design (Art Prompt, Illustration)
  - Developer (code snippet, tool generator)
  - Student (essay, study summary, quiz)
- Interactive prompt builder

### 💬 Prompt Chat

- Conversational interface for prompt creation
- Step-by-step prompt generation
- Session saving and management

## 🛠️ Technical Stack

### Frontend

- React Native + Expo (mobile)
- React + Tailwind (web)

### Backend

- **Framework**: NestJS
- **ORM**: TypeORM
- **Authentication & Storage**: Firebase
- **Database**: PostgreSQL
- **AI Integration**: OpenAI GPT-4 API
- **Payment Processing**: Stripe SDK
- **Deployment**:
  - Frontend: Vercel (web), Expo EAS (mobile)
  - Backend: Fly.io

## 💎 Subscription Tiers

### Free Tier

- Limited prompt creation per month
- Basic prompt management
- Access to public templates

### Pro Tier

- Unlimited prompt creation
- AI optimization features
- Marketplace access
- Advanced templates
- Priority support

## 🚀 Getting Started

1. Clone the repository
2. Install dependencies
3. Set up environment variables
4. Run the development server

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

## ⚙️ Environment Variables

```env
# Backend (.env)
DATABASE_URL=postgresql://user:password@localhost:5432/prompt_db
FIREBASE_API_KEY=your_firebase_api_key
FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
FIREBASE_PROJECT_ID=your_firebase_project_id
FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
FIREBASE_APP_ID=your_firebase_app_id
OPENAI_API_KEY=your_openai_api_key
STRIPE_SECRET_KEY=your_stripe_secret_key
```

## 📞 Support

For support, email [support@promptplatform.com](mailto:support@promptplatform.com)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
  <sub>Built with ❤️ by the Prompt Management Platform Team</sub>
</div>
