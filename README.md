# Portfolio-website-
P# Annebelle Phanor - Portfolio Website

A modern, professional portfolio website showcasing expertise in data analytics and software development with creative design elements.

## About

This portfolio website highlights my journey as a recent Computer Science graduate from CUNY - York College, specializing in data analytics and software development. The site combines technical innovation with creative design to showcase my unique approach to transforming data into compelling visual stories.

## Features

- **Modern Design**: Neutral color palette with strategic pops of color (emerald, teal, coral, violet, amber)
- **Interactive Elements**: Animated skill bars, smooth scrolling navigation, and responsive design
- **Personal Branding**: Authentic images including personal photo, project logos, and university branding
- **Professional Sections**: Hero, About, Experience, Projects, Skills, Education, and Contact
- **Database Integration**: PostgreSQL backend for contact form persistence
- **Mobile Responsive**: Optimized for all device sizes

## Tech Stack

### Frontend
- React 18+ with TypeScript
- Vite for fast development and optimized builds
- Tailwind CSS with custom design system
- Shadcn/ui components built on Radix UI
- React Query for server state management
- Wouter for lightweight routing

### Backend
- Node.js with Express.js
- TypeScript with ES modules
- Drizzle ORM for type-safe database operations
- PostgreSQL database via Neon serverless
- RESTful API design

### Deployment
- Replit for development and hosting
- Environment-based configuration
- Automated build and deployment pipeline

## Key Sections

### Hero Section
- Personal photo and professional introduction
- Captivating tagline: "Where Data Meets Creativity"
- Call-to-action buttons with smooth navigation

### Featured Projects
1. **DermyEqua** - AI-powered skincare consultant (In Development)
2. **Sebannix** - Health recruiting website (Live)
3. **Weather Impact Analysis** - Data analysis research project

### Skills & Expertise
- Technical skills with animated progress bars
- Tools and technologies showcase
- Soft skills with icon representations

### Experience
- Current role at Walgreens Boots Alliance
- Focus on beauty & wellness market analysis
- Recent graduate perspective

## Getting Started

### Prerequisites
- Node.js 18+ 
- PostgreSQL database
- Environment variables for database connection

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/annebelle-portfolio.git
cd annebelle-portfolio
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
```bash
# Add your database URL
DATABASE_URL=your_postgresql_connection_string
```

4. Start development server
```bash
npm run dev
```

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run db:push` - Sync database schema
- `npm run check` - TypeScript type checking

## Project Structure

```
├── client/                 # Frontend React application
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Page components
│   │   ├── assets/         # Images and static files
│   │   └── lib/            # Utilities and configurations
├── server/                 # Backend Express application
│   ├── routes.ts           # API route definitions
│   ├── storage.ts          # Database operations
│   └── db.ts              # Database configuration
├── shared/                 # Shared types and schemas
│   └── schema.ts          # Database schema definitions
└── components.json         # Shadcn/ui configuration
```

## Design Philosophy

This portfolio embodies the concept of "creative analytics" - where technical precision meets artistic expression. The design features:

- **Neutral Foundation**: Professional gray tones as the primary palette
- **Strategic Color Pops**: Emerald, teal, coral, violet, and amber for emphasis
- **Authentic Imagery**: Personal photos and actual project assets
- **Smooth Interactions**: Subtle animations and transitions
- **Accessibility**: High contrast and keyboard navigation support

## Contact

- **Email**: [Your Email]
- **LinkedIn**: [Your LinkedIn]
- **GitHub**: [Your GitHub]
- **Website**: [Your Portfolio URL]

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*"Turning numbers into narratives, insights into impact"*
