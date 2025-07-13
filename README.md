🌟 Build a Full Stack Job Portal
This project is a modern, responsive Job Portal application built with React JS, Tailwind CSS, Supabase, Clerk Authentication, and Shadcn UI. It allows employers to post jobs and candidates to browse and apply for them, demonstrating a real-world full-stack workflow with a focus on modern developer tooling.

🚀 Features
User Authentication & Authorization

Powered by Clerk for secure, production-ready sign-up, login, and session management.

Supports social logins and magic links (if enabled in Clerk).

Role-based Access

Employers can create and manage job listings.

Job seekers can browse and apply to jobs.

Real-Time Database

Uses Supabase as the backend (PostgreSQL + realtime).

Supports real-time updates for new job postings.

Modern UI Components

Built with Shadcn UI, offering clean, accessible, and customizable React components.

Responsive Design

Fully mobile-friendly with Tailwind CSS.

Dark mode support (optional).

Dashboard Views

Employer dashboard: Post jobs, view listings, manage applicants.

Candidate dashboard: View applied jobs, save favorites.

Application Form

Streamlined job application process.

Form validation and submission to Supabase.

Data Management

Supabase CRUD for jobs, users, applications.

Secure access controls enforced via Row Level Security (RLS).

🛠️ Technologies Used
Frontend

React JS (with Vite or CRA)

Tailwind CSS

Shadcn UI

Clerk (Authentication)

Backend

Supabase (PostgreSQL Database + Auth + Storage)

Other

React Router (for navigation)

React Hook Form / Zod (for form validation)

Supabase Client Library

Clone this repo and install dependencies:

git clone https://github.com/your-username/job-portal
cd job-portal
npm install

Set up environment variables (example):

VITE_SUPABASE_URL=your-supabase-url
VITE_SUPABASE_ANON_KEY=your-supabase-anon-key
VITE_CLERK_PUBLISHABLE_KEY=your-clerk-publishable-key

