# Dashboard Frontend

This repository contains the frontend application for a dashboard, built with React and Vite. It utilizes various UI components from Radix UI and styling with Tailwind CSS to provide a modern and responsive user interface. The application integrates with a backend (not included in this repository) to fetch and manage data.

## Features

- **Modern UI:** Built with React, Radix UI, and Tailwind CSS for a clean and responsive design.
- **Data Visualization (Implied):** Likely displays various data points and metrics relevant to a dashboard.
- **Form Handling:** Uses `react-hook-form` and `zod` for robust form validation.
- **State Management:** Utilizes Redux Toolkit for efficient state management.
- **Routing:** Implements client-side routing with `react-router-dom`.
- **API Integration:** Uses Axios for making HTTP requests to a backend API.
- **Notifications:** Integrates `react-toastify` for user feedback and notifications.
- **PDF Viewer:** Includes `react-pdf` for displaying PDF documents.

## Technologies Used

- **React:** A JavaScript library for building user interfaces.
- **Vite:** A fast build tool that provides a lightning-fast development experience.
- **Tailwind CSS:** A utility-first CSS framework for rapidly building custom designs.
- **Radix UI:** A collection of unstyled, accessible UI components.
- **Redux Toolkit:** The official, opinionated, batteries-included toolset for efficient Redux development.
- **React Router DOM:** Declarative routing for React.
- **Axios:** Promise-based HTTP client for the browser and Node.js.
- **React Hook Form:** Performant, flexible and extensible forms with easy-to-use validation.
- **Zod:** A TypeScript-first schema declaration and validation library.
- **Lucide React:** A beautiful, customizable icon library.
- **React Toastify:** A library for adding toast notifications to your React apps.
- **React PDF:** A React component for displaying PDFs.

## Setup and Installation

To get this project up and running on your local machine, follow these steps:

### Prerequisites

- Node.js (LTS version recommended)

### 1. Clone the repository

```bash
git clone <repository-url>
cd dashboard
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Running the Application

#### Development Mode

To run the application in development mode with Vite's hot-reloading:

```bash
npm run dev
```

This will start the development server, usually at `http://localhost:5173`.

#### Building for Production

To build the application for production:

```bash
npm run build
```

This will create a `dist` directory with the optimized production build.

#### Previewing Production Build

To preview the production build locally:

```bash
npm run preview
```