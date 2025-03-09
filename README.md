# Lawn Refresh SaaS MVP

A React Native (Expo) application for lawn care service booking.

## Project Overview

Lawn Refresh is a SaaS platform that connects lawn care service providers with customers. This application allows customers to book lawn care services, and providers to manage their schedules and services.

## Tech Stack

- **Frontend**: React Native (Expo)
- **UI Components**: NativeBase
- **State Management**: Zustand (to be implemented)
- **Backend**: Supabase (PostgreSQL, Authentication, Storage)
- **Payments**: Stripe

## Project Structure

```
project/
├── app/                      # Expo Router pages
├── src/                      # Source code
│   ├── components/           # Reusable UI components
│   │   ├── common/           # Generic UI elements
│   │   ├── examples/         # Component examples
│   ├── providers/            # Context providers
│   ├── api/                  # API integration (to be implemented)
│   ├── hooks/                # Custom React hooks (to be implemented)
│   ├── store/                # Zustand state management (to be implemented)
│   ├── types/                # TypeScript type definitions (to be implemented)
│   ├── utils/                # Utility functions (to be implemented)
│   └── constants/            # App constants (to be implemented)
└── assets/                   # Static assets
```

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or yarn
- Expo CLI

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/momomojo/cursor.lawnrefresh.git
   cd cursor.lawnrefresh
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server
   ```bash
   npm run dev
   # or
   yarn dev
   ```

## Current Progress

- Set up project structure
- Integrated NativeBase UI component library
- Created reusable Button component
- Created component examples showcase

## Next Steps

- Implement Supabase client integration
- Set up authentication flow
- Create API services for core entities
- Implement Zustand state management
- Build additional UI components

## License

This project is proprietary and confidential.