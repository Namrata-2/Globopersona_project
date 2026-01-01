# Globopersona UI Redesign

Modern, clean, and fully interactive UI redesign for the Globopersona Email Marketing Platform.

## Key Features
- **Secure Authentication**: Strict login and signup flow. Users must register to access the dashboard.
- **Dynamic Dashboard**: Interactive stat cards and real-time data visualization.
- **Personalized Experience**: User profiles with custom avatars, mobile numbers, and settings.
- **Email Lists & Contacts**: Full CRUD functionality with search and filtering.
- **Campaign Management**: Interactive campaign creation flow.
- **Responsive Design**: Mobile-first architecture with collapsible navigation.

## Tech Stack
- **React 18** + **Vite**
- **Tailwind CSS** for styling
- **Lucide React** for iconography
- **React Router** for navigation
- **Context API** for global state management

## How to Run

### Prerequisites
- Node.js installed on your machine.

### Steps
1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the development server:
   ```bash
   npm run dev
   ```
3. Open your browser at `http://localhost:5173`.

### Usage Guide
- **Login**: Use default credentials (`namrata@globopersona.com`) or create a new account.
- **Strict Mode**: Unregistered emails are blocked from logging in.
- **Settings**: Visit the Settings page to update your profile photo and mobile number.

## Project Structure
- `src/components`: Reusable UI atoms (Button, Card, Input, etc.).
- `src/layouts`: Main layout wrapper (Sidebar + Header).
- `src/pages`: Individual screen implementations (Dashboard, Login, Settings, etc.).
- `src/context`: State management and mock authentication logic.
