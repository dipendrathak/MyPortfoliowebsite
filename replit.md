# Overview

This is a modern personal portfolio website for Dipendra Kumar Thakur, a geomatics engineering student and passionate teacher. The application is built as a full-stack web application with a React frontend and Express backend, showcasing Dipendra's real academic background from IOE Paschimanchal Campus Pokhara, technical skills including GIS tools and programming languages, teaching experience, and projects. The portfolio includes sections for hero introduction, about, skills, projects, teaching services, YouTube channel, resume downloads, and a contact form with his actual contact information (phone: +977 982-4663366, email: thakurnikee47@gmail.com).

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Framework**: React 18 with TypeScript
- **Build Tool**: Vite for fast development and optimized production builds
- **Routing**: Wouter for lightweight client-side routing
- **UI Components**: Shadcn/ui component library built on Radix UI primitives
- **Styling**: Tailwind CSS with custom CSS variables for theming
- **State Management**: TanStack Query (React Query) for server state management
- **Forms**: React Hook Form with Zod validation
- **Theme System**: Custom theme provider supporting light/dark modes

## Backend Architecture
- **Framework**: Express.js with TypeScript
- **Database ORM**: Drizzle ORM configured for PostgreSQL
- **Database Provider**: Neon Database (serverless PostgreSQL)
- **API Design**: RESTful endpoints for contact form submissions
- **Validation**: Zod schemas for request validation
- **Storage**: In-memory storage implementation with interface for future database integration
- **Development**: Custom Vite integration for SSR-like development experience

## Data Layer
- **Schema**: Defined in shared directory using Drizzle ORM
- **Contact Messages**: PostgreSQL table with fields for name, email, subject, message, and timestamps
- **Type Safety**: Full TypeScript integration from database to frontend using Drizzle's type inference

## Project Structure
- **Monorepo Setup**: Single repository with client, server, and shared code
- **Client Directory**: Contains React frontend application
- **Server Directory**: Contains Express backend application  
- **Shared Directory**: Contains common schemas and types
- **Path Aliases**: Configured for clean imports (@/, @shared/, @assets/)

## Development Features
- **Hot Module Replacement**: Vite HMR for fast development
- **TypeScript**: Full type safety across the entire application
- **Error Handling**: Custom error overlay for development
- **Replit Integration**: Specialized plugins for Replit development environment

# External Dependencies

## Database & Infrastructure
- **Neon Database**: Serverless PostgreSQL database provider
- **Drizzle Kit**: Database migration and schema management tool

## UI & Styling
- **Tailwind CSS**: Utility-first CSS framework
- **Radix UI**: Headless UI components for accessibility
- **Shadcn/ui**: Pre-built component library
- **Lucide React**: Icon library for consistent iconography
- **PostCSS**: CSS processing with Autoprefixer

## Development & Build Tools
- **Vite**: Frontend build tool and development server
- **TSX**: TypeScript execution for server development
- **ESBuild**: Fast JavaScript bundler for production builds

## Frontend Libraries
- **TanStack Query**: Server state management and caching
- **React Hook Form**: Form state management and validation
- **Wouter**: Lightweight client-side routing
- **Date-fns**: Date utility library
- **Class Variance Authority**: Utility for conditional CSS classes

## Backend Libraries
- **Zod**: Schema validation and type inference
- **Drizzle-Zod**: Integration between Drizzle ORM and Zod validation
- **Connect-PG-Simple**: PostgreSQL session store (configured but not actively used)
- **Nanoid**: URL-safe unique ID generator

## Image & Media
- **Unsplash**: External image service for placeholder images and project visuals

## Fonts & Typography
- **Google Fonts**: Inter font family for modern typography
- **Custom Font Variables**: CSS custom properties for font management