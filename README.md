# Content Generation System - AI powered SAAS application

## Overview

The **Content Generation System** is an AI-powered web platform that provides seamless text generation, AI image creation, and data visualization capabilities. Built using **Next.js**, the project integrates various APIs and technologies to offer a user-friendly, efficient, and scalable solution.

🔗 **Live Demo :** [Content Generation System](https://content-generation-system.onrender.com)\
📄 **Research Paper published at IJARESM** : [Leveraging Generative AI for an Advanced Content Generation System](https://www.ijaresm.com/leveraging-generative-ai-for-an-advanced-content-generation-system-a-comprehensive-framework)

## Features

- **AI-Powered Text Generation** – Uses **Gemini API** for generating, refining, and analyzing textual content.
- **AI Image Generation** – Leverages **Stability AI** for creating high-quality AI-generated images.
- **Interactive Data Visualization** – Supports **Recharts + XLSX** for processing and visualizing Excel-based datasets.
- **Secure Authentication** – Implements **Clerk API** for seamless user authentication and session management.
- **Subscription-Based Access** – Integrates **Razorpay** for payment processing and managing premium subscriptions.
- **Optimized Database Management** – Utilizes **PostgreSQL + Drizzle ORM** for efficient data handling.
- **Responsive UI & UX** – Built with **Next.js** and **ShadCN** for a clean, modern, and dynamic interface.
- **Server-Side Rendering (SSR)** – Ensures faster load times and improved performance.

---

## Tech Stack

### Frontend:

- **Next.js (TypeScript)** – React framework with built-in SSR and API routes.
- **React.js** – UI library for dynamic frontend rendering.
- **ShadCN (UI Library)** – Pre-built components for a consistent and responsive design.

### Backend:

- **Next.js API Routes** – Acts as the backend with built-in API handling.
- **TypeScript** – Ensures type safety and robustness.
- **Express.js (Node.js)** – Used in standalone API handling (if required).
- **PostgreSQL** – Relational database for structured data management.
- **Drizzle ORM** – TypeScript ORM for querying and managing the database.

### APIs Used:

- **Gemini API** – AI-powered text generation.
- **Stability AI** – AI-based image generation.
- **Clerk API** – User authentication and session management.
- **Razorpay API** – Payment processing and subscription management.
- **Recharts + XLSX** – Data visualization from Excel files.

---

## Installation & Setup

### Prerequisites:

- Node.js v16+
- PostgreSQL Database
- API Keys for **Gemini**, **Stability AI**, **Clerk**, and **Razorpay**

### Steps to Run:

#### 1. Clone the Repository:

```bash
git clone https://github.com/hrithikksingh3/Content-generation-system.git
cd content-generation-system
```

#### 2. Install Dependencies:

```bash
npm install  # or yarn install
```

#### 3. Set Up Environment Variables:

Create a `.env.local` file in the root directory and add:

```env
NEXT_PUBLIC_CLERK_API_KEY=your_clerk_api_key
NEXT_PUBLIC_GEMINI_API_KEY=your_gemini_api_key
NEXT_PUBLIC_STABILITY_AI_KEY=your_stability_ai_key
NEXT_PUBLIC_RAZORPAY_KEY=your_razorpay_key
DATABASE_URL=your_postgresql_database_url
```

#### 4. Run the Application:

```bash
npm run dev  # Start development server
```

By default, the frontend runs on **[http://localhost:3000](http://localhost:3000)**.


## Usage Guide

### 1. User Authentication (Clerk)

- Users sign up or log in via **Clerk authentication**.
- Upon login, users access basic or **Pro features** based on their subscription status.

### 2. AI Text Generation (Gemini API)

- Navigate to the **Text Generation** page.
- Input prompts and receive AI-generated text.

### 3. AI Image Generation (Stability AI)

- Enter a prompt for the AI model.
- Click generate to get AI-created images.

### 4. Data Visualization (Excel Upload)

- Upload an Excel file containing structured data.
- Choose columns for X and Y axes.
- Generate dynamic **Bar, Line, or Pie charts**.

### 5. Subscription & Payments (Razorpay)

- Users can upgrade to Pro by making a payment via **Razorpay**.
- Subscription unlocks **higher usage limits** for AI services.

---

## Deployment

### Deploying on Vercel:

```bash
npm run build
vercel deploy
```

Ensure `.env.local` is properly configured in Vercel’s dashboard.

### Deploying Backend (Optional):

- If using a separate **Express.js backend**, deploy it on **Render, Railway, or AWS**.

---

## Future Enhancements

- Implement **AI-powered document summarization**.
- Add **real-time collaboration features** for content editing.
- Improve **data analytics tools** with advanced visualizations.
- Expand **multi-language support** for text and image generation.

---

## Contributors

- **Hrithik Kumar Singh** – Lead Developer & Project Architect
- **Kalpana Bharti** 
- **Kiran Sharma** 
- **Shiven Pokhriyal** 

---

## License

This project is licensed under the **MIT License**.

## Contact

For any questions or feedback, feel free to reach out to me.
