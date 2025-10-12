# Jobify

Jobify is a modern job management platform built with cutting-edge technologies for rapid development, scalability, and great user experience. It lets users track their job application in various companies, allowing users to change the status of application. It basically shows a list of jobcards , statistics of applicationby month or week. It also lets users search for a praticular job using the name of company, type of role, location etc. 

## Tech Stack

- **Next.js 14** – React framework for building fast, scalable web applications.
- **TypeScript** – Type-safe, modern JavaScript development.
- **Prisma** – Next-generation ORM for database management.
- **Clerk** – Authentication and user management.
- **shadcn/ui** – Beautiful, customizable UI components.
- **Zod** – Type-safe schema validation.
- **TailwindCSS** (+ tailwind-merge, tailwindcss-animate) – Utility-first CSS framework.
- **React Hook Form** – Form state management.
- **Radix UI** – Low-level UI primitives for React.
- **TanStack Query** – Powerful data fetching & caching for React apps.
- **Lucide React** – Icon library.
- **Recharts** – Charting library for React.
- **Day.js** – Lightweight date library.

## Features

- 🔑 Secure authentication & user management (Clerk)
- ⚡ Fast performance & SSR/SSG (Next.js)
- 🎨 Modern, responsive UI (shadcn/ui, TailwindCSS)
- 📦 Type-safe backend & validation (TypeScript, Zod, Prisma)
- 📊 Visual data representation (Recharts)
- 🧩 Modular, scalable architecture

## Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/SubhamsSharma/jobify.git
   cd jobify
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   - Copy `.env.example` to `.env.local` and set your database URL, Clerk keys, etc.

4. **Generate Prisma Client**
   ```bash
   npx prisma generate
   ```

5. **Run the development server**
   ```bash
   npm run dev
   ```

6. **Open [http://localhost:3000](http://localhost:3000) in your browser**

## Scripts

- `npm run dev` – Start development server
- `npm run build` – Build for production
- `npm start` – Start production server
- `npm run lint` – Run linter

## Project Structure

- `/app` – Next.js app directory
- `/prisma` – Prisma schema & migration files
- `/components` – Reusable React components
- `/lib` – Helper libraries
- `/styles` – Global styles

## Contributing

Contributions are welcome! Please open issues, submit pull requests, or contact the maintainer.

## License

This project is licensed under the MIT License.

---

Built with ❤️ by [SubhamsSharma](https://github.com/SubhamsSharma)
