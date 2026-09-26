# API Management Frontend

## Backend Repository

You can find the backend code here: [Backend Repo](https://github.com/<your-username>/API_Backend.git)

## Overview

This is the frontend for the API Management System, providing a user-friendly interface for managing API keys, monitoring analytics, and configuring API settings. It is built using React and communicates with the backend for authentication and data retrieval.

## Architecture

- **React.js** - Frontend framework
- **React Router** - Handles navigation
- **Axios** - For making API requests
- **Context API** - State management
- **Tailwind CSS** - Styling

## Features

- **User Authentication**: Secure login and registration.
- **Dashboard**: View API analytics and manage API keys.
- **API Key Management**: Generate, view, and delete API keys.
- **Usage Monitoring**: Track API request counts and performance.
- **Dark Mode Support**: UI theme toggle.

## Setup Instructions

Ensure you have **Node.js** and **npm** installed.

### Steps:

1. Clone the repository:

```
git clone https://github.com/<your-username>/API_Management_System.git
cd API_Management_System
```

2. Install dependencies:

```
npm install
```

3. Create a `.env` file in the root directory with the following variables:

```
VITE_BACKEND_URL=http://localhost:5000
```

4. Start the development server:

```
npm run dev
```

5. The frontend should now be running at `http://localhost:5173`.
