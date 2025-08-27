# Crime Prediction Analytics

## Overview

This is an AI-powered crime prediction system that uses machine learning to forecast crime rates and patterns for Indian cities. The application provides interactive crime analytics, risk assessments, and data visualizations to help understand crime trends and make informed predictions about future crime patterns.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React with TypeScript for type safety and component-based architecture
- **Routing**: Wouter for lightweight client-side routing
- **UI Components**: Shadcn/UI component library built on Radix UI primitives for consistent design
- **Styling**: Tailwind CSS with custom CSS variables for theming and responsive design
- **State Management**: TanStack React Query for server state management and caching
- **Forms**: React Hook Form with Zod validation for type-safe form handling
- **Charts**: Custom canvas-based charts for crime data visualization (trends and distribution charts)

### Backend Architecture
- **Runtime**: Node.js with Express.js framework
- **Language**: TypeScript with ES modules for modern JavaScript features
- **API Design**: RESTful API endpoints for city search, crime predictions, and data retrieval
- **Error Handling**: Centralized error handling middleware with proper HTTP status codes
- **Logging**: Request/response logging for API monitoring and debugging

### Data Layer
- **Database**: PostgreSQL with Drizzle ORM for type-safe database operations
- **Connection**: Neon Database serverless PostgreSQL for cloud-hosted data storage
- **Schema**: Structured tables for users, cities, crime data, and predictions with proper relationships
- **Migrations**: Database migrations managed through Drizzle Kit
- **Fallback Storage**: In-memory storage implementation for development and testing

### ML Prediction Service
- **Algorithm**: Simple linear regression for crime rate prediction based on historical data
- **Data Processing**: Statistical analysis of historical crime patterns and trends
- **Risk Assessment**: Automated risk level classification (LOW, MODERATE, HIGH) based on crime rates
- **Comparative Analysis**: Similar city comparisons and crime distribution analysis
- **Confidence Scoring**: Prediction confidence based on historical data availability and trend consistency

### Development and Build System
- **Build Tool**: Vite for fast development and optimized production builds
- **Development**: Hot module replacement and development server integration
- **Production**: Optimized bundling with separate client and server builds
- **Type Checking**: TypeScript compiler for static type analysis
- **Path Aliases**: Absolute imports with custom path mapping for better code organization

## External Dependencies

### Database Services
- **Neon Database**: Serverless PostgreSQL database hosting
- **Drizzle ORM**: Type-safe database ORM with PostgreSQL dialect
- **Database Connection**: Environment-based configuration with connection pooling

### UI and Styling
- **Radix UI**: Accessible component primitives for complex UI components
- **Tailwind CSS**: Utility-first CSS framework with custom design system
- **Lucide React**: Icon library for consistent iconography
- **Google Fonts**: Web fonts (Inter, Architects Daughter, DM Sans, Fira Code, Geist Mono)

### Development Tools
- **Replit Integration**: Development environment integration with error overlay and cartographer
- **PostCSS**: CSS processing with Tailwind CSS and Autoprefixer
- **ESBuild**: Fast JavaScript bundler for server-side code

### Runtime Libraries
- **TanStack React Query**: Server state management and data fetching
- **React Hook Form**: Form state management and validation
- **Zod**: Runtime type validation and schema parsing
- **Date-fns**: Date manipulation and formatting utilities
- **Class Variance Authority**: Utility for creating type-safe CSS class variants