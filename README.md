# PrepWise

**AI-Powered Interview Practice Platform**

PrepWise is a sophisticated web application that leverages artificial intelligence to provide realistic interview practice sessions. The platform generates personalized technical and behavioral interview questions tailored to specific roles and tech stacks, then conducts live voice interviews using advanced AI agents. Users receive detailed feedback and scoring across multiple evaluation criteria, helping them improve their interview performance before the real thing.

## Key Features

- **AI-Generated Custom Interviews** - Dynamic question generation based on role, experience level, and technology stack
- **Real-Time Voice Interviews** - Interactive voice conversations with AI interviewers using VAPI integration
- **Comprehensive Feedback System** - Detailed scoring across 5 categories: Communication Skills, Technical Knowledge, Problem Solving, Cultural Fit, and Confidence & Clarity
- **Multi-Technology Support** - Covers 80+ technologies including React, Node.js, Python, AWS, Docker, and more
- **Interview Management Dashboard** - Track past interviews, view feedback, and monitor progress over time
- **Flexible Interview Types** - Choose between technical-focused, behavioral-focused, or mixed interview formats
- **Experience Level Targeting** - Tailored questions for Junior, Mid-Level, and Senior positions
- **Responsive Design** - Optimized for both desktop and mobile interview sessions

## Technologies Used

**Frontend**

- Next.js 15 (React 19) with App Router
- TypeScript for type safety
- Tailwind CSS for modern, responsive styling
- Radix UI components for accessible UI elements
- React Hook Form with Zod validation

**Backend & AI Integration**

- Google Gemini 2.0 Flash for intelligent question generation
- VAPI for real-time voice interview capabilities
- Firebase Firestore for data persistence
- Firebase Admin SDK for server-side operations

**Development Tools**

- ESLint and Prettier for code quality
- Turbopack for fast development builds
- dayjs for date formatting and manipulation

## Implementation Highlights

**Voice AI Integration**: The platform integrates with VAPI to create natural, conversational interview experiences. The AI interviewer is configured with professional prompting to conduct realistic interviews while maintaining appropriate pacing and follow-up questions.

**Dynamic Question Generation**: Uses Google's Gemini 2.0 Flash model to generate contextually relevant interview questions based on job requirements. The system maps 80+ technology variants to standardized icons and handles complex tech stack combinations.

**Structured Feedback System**: Implements a comprehensive scoring rubric that evaluates candidates across multiple dimensions, providing actionable insights for improvement.

**Type-Safe Architecture**: Full TypeScript implementation with carefully designed interfaces for interviews, feedback, users, and API responses ensures robust data handling.

## My Role & Contributions

As the sole developer, I built the entire platform with the help of an online tutorial for the VAPI piece, including:

- Designed the complete system architecture and data models
- Implemented real-time voice AI integration with VAPI
- Built the dynamic question generation system using Google's Gemini API
- Created a responsive, accessible UI with modern design principles
- Established Firebase backend infrastructure and data persistence layer
- Developed comprehensive TypeScript type definitions for type safety
- Implemented user authentication and session management

## Getting Started

### Prerequisites

- Node.js 18+
- Firebase project with Firestore enabled
- VAPI account for voice AI features
- Google AI Studio API key

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd prepwise

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
# Add your Firebase, VAPI, and Google AI credentials

# Run the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to access the application.

### Build for Production

```bash
npm run build
npm start
```

## Use Case

**Target Users:**

- **Job Seekers** preparing for technical interviews at tech companies
- **Recent Graduates** looking to practice interview skills before entering the job market
- **Career Changers** transitioning into new technology roles
- **Professionals** seeking promotion opportunities requiring interview preparation

**Ideal Team Scenarios:**

- **Recruiting Teams** offering candidates practice opportunities before final interviews
- **Bootcamps and Educational Institutions** providing students with realistic interview preparation
- **Corporate Training Programs** helping internal candidates prepare for advancement opportunities

This project demonstrates proficiency in modern web development, AI integration, real-time communication systems, and creating user-centric applications that solve real-world problems in professional development.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
