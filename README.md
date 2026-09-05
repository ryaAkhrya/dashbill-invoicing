# DashBill

A bold, lightweight invoicing app for freelancers.

DashBill helps freelancers manage clients, create invoices, track payment status, and export professional PDFs without unnecessary complexity.

## Live Demo

https://dashbill-three.vercel.app

## Features

- Username-based authentication
- Client management
- Invoice creation
- Automatic subtotal, tax, and total calculations
- Invoice status tracking
- PDF export
- Per-user data isolation with Supabase RLS
- Responsive dashboard
- Mobile-friendly interface

## Tech Stack

- Next.js
- TypeScript
- React
- Tailwind CSS
- Supabase
- PostgreSQL
- jsPDF

## Core Pages

- Landing Page
- Login / Signup
- Dashboard Overview
- Clients
- Invoices
- New Invoice Builder

## Security

DashBill uses Supabase Row Level Security to isolate user-owned data.

Authentication, user ownership, and data access are enforced server-side.

## Local Development

Clone the repository:

```bash
git clone https://github.com/ryaAkhrya/dashbill.git
cd dashbill
