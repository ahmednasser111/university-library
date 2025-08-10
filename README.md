# 📚 University Library Management System

A modern, full-featured University Library Management System built with Next.js, TypeScript, PostgreSQL, and Tailwind CSS. This project provides a robust platform for managing library resources, users, and administrative workflows, with a clean and responsive UI.

## 🚀 Features

- **Authentication**: Secure onboarding with email notifications.
- **Home Page**: Highlights featured and new books.
- **Library Page**: Advanced filtering, search, and pagination.
- **Book Details**: Availability, summaries, videos, and recommendations.
- **Profile Management**: Track borrowed books, download receipts.
- **Automated Workflows**: Welcome emails, reminders, and follow-ups.
- **Borrow Reminders**: Email notifications for due dates.
- **PDF Receipts**: Auto-generated when borrowing books.
- **Admin Dashboard**: Analytics, user management, and book management.
- **Role Management**: Assign admin/user roles with notifications.
- **Database Management**: PostgreSQL with Drizzle ORM.
- **Caching**: Upstash Redis for performance.
- **Media Optimization**: ImageKit for images and videos.
- **Modern UI/UX**: Built with TailwindCSS and ShadCN.

## 🛠️ Tech Stack

- Next.js
- TypeScript
- PostgreSQL
- Drizzle ORM
- Upstash Redis
- ImageKit
- Resend (for emails)
- Tailwind CSS

## ⚡ Quick Start

### Prerequisites

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

### Clone the Repository

```bash
git clone <your-repo-url>
cd university-library
```

### Install Dependencies

```bash
npm install
```

### Set Up Environment Variables

Create a `.env` file in the root directory and add:

```env
NEXT_PUBLIC_IMAGEKIT_PUBLIC_KEY=
IMAGEKIT_PRIVATE_KEY=
NEXT_PUBLIC_IMAGEKIT_URL_ENDPOINT=

NEXT_PUBLIC_API_ENDPOINT=
NEXT_PUBLIC_PROD_API_ENDPOINT=

DATABASE_URL=

UPSTASH_REDIS_URL=
UPSTASH_REDIS_TOKEN=

AUTH_SECRET=

QSTASH_URL=
QSTASH_TOKEN=

RESEND_TOKEN=
```

Replace the values with your own credentials from [ImageKit](https://imagekit.io/), [NeonDB](https://neon.tech/), [Upstash](https://upstash.com/), and [Resend](https://resend.com/).

### Run the Project

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) in your browser.

## 🖼️ Assets

- Project assets can be found in the `public` and `app/fonts` directories.

## 📂 Project Structure

- `app` - Main application pages and layouts
- `components` - Reusable UI components
- `constants` - Static data and configuration
- `database` - Database schema and seed scripts
- `hooks` - Custom React hooks
- `lib` - Utility functions and server logic
- `styles` - Global and admin CSS
- `public` - Static assets

## 📑 License

This project is open-source and available under the MIT License.