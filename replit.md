# Twin Perceptions Community Platform

## Overview
Twin Perceptions is a sacred, intuitive digital sanctuary for healing, learning, and connection through holistic aromatherapy, energy work, and guided ritual. It aims to provide emotional safety, spiritual resonance, and affirmational care, embodying the soul of Twin Perceptions. The platform is designed to be a comprehensive spiritual community hub, offering resources for personal growth and collective wisdom.

## User Preferences
- **Color Palette:** Sacred and mystical colors
  - Soft lavenders (hsl(270, 35%, 75%))
  - Moss greens (hsl(120, 25%, 45%))
  - Moonstone greys (hsl(220, 10%, 70%))
  - Gold accents (hsl(45, 85%, 65%))
  - Ethereal backgrounds with gentle gradients
- **Typography:** Warm serif body text, handwritten script for headers and affirmations
- **Design Philosophy:** Sacred sanctuary feel with botanical imagery, candlelight aesthetics, and spiritual symbolism
- **Tone:** Soothing, sacred, empathetic—user-first, soul-forward approach

## System Architecture
The platform is built with a **React (TypeScript) frontend** and an **Express (TypeScript) backend**.
- **Frontend:** Utilizes Wouter for routing, TanStack Query for server state management, and shadcn/ui with Tailwind CSS for UI components. Key pages include a Homepage, Essential Oils Database, Community Forum, Educational Content, and Subscription/Consultation Management.
- **Backend:** Employs in-memory storage (MemStorage) for development, with RESTful API endpoints for managing oils, posts, users, subscriptions, consultations, and massage bookings. Zod schemas are used for data validation.
- **Core Modules & Features:**
    - **The Scented Library:** An Essential Oil Wisdom Hub detailing emotional, spiritual, and chakra associations. Includes comprehensive data on essential oils, carrier oils, therapeutic properties, and blending education.
    - **The Story Circle:** A community space for sharing healing stories with filtering capabilities.
    - **Echoes of Insight:** A curated wisdom repository featuring community quotes, scent pairings, and ritual suggestions.
    - **Sacred Sanctuary Subscription System:** Manages subscriptions, consultations, and payment processing. Includes tiered membership (Free, Standard, Premium, Elite) with tiered access control and PayPal/Stripe integrations.
    - **Authentication System:** Comprehensive user registration, login, logout, session management, and role-based access control with admin privileges. Includes activity tracking for user interactions.
    - **Blog System:** Functionality for creating, managing, and displaying blog posts with image uploads.
    - **Celestial Room:** The energetic nucleus featuring daily moon phase reflections, an energy tracker, Light Ritual Mode, Crystal Charging Guide, Guided Meditations, and an ambient soundscape library.
    - **Celestial Calendar:** Dynamic moon phase tracking, sacred portal days, and moon-phase specific insights and ritual suggestions.
    - **Massage Therapy Services:** Includes a comprehensive calendar-based booking system for professional massage services with medical form integration.
    - **User Experience:** Features a consistent cosmic color scheme with soft lavenders, moss greens, moonstone greys, and gold accents. Typography uses warm serifs and handwritten scripts. Design emphasizes a sacred sanctuary feel with botanical imagery, candlelight aesthetics, and spiritual symbolism. Accessibility is prioritized with high contrast, responsive design, and animations/sound toggles. Interactive onboarding guides users through features.

## External Dependencies
- **Payment Processors:** PayPal, Stripe (for debit cards, Apple Pay, Google Pay)
- **Analytics:** Google Analytics 4
- **UI Framework:** shadcn/ui
- **CSS Framework:** Tailwind CSS
- **Routing Library:** Wouter
- **State Management:** TanStack Query
- **Validation:** Zod
- **Hashing:** bcryptjs
- **Session Management:** express-session
- **File Uploads:** Multer (for blog image uploads)
- **Icons:** Lucide React (for social media icons)
- **Database:** PostgreSQL (for production, currently in-memory for development)