# Expense Tracking Application - Backend

A MERN-Stack application for AussenDienst GmbH to manage and track travel expenses for sales representatives.

## Project Structure

This is the **backend API** repository. The frontend React application is available at:
**Frontend Repository**: [mh-expenses-app-render-frontend-v2](https://github.com/marcelhess/mh-expenses-app-render-frontend-v2)

## Features

- User authentication with role-based access control
- RESTful API for expense management
- Google Maps integration for route calculation
- Automatic expense calculation based on predefined rates
- Analytics endpoints for expense data
- Export functionality for reports (PDF, CSV)
- Comprehensive logging and error handling

## Tech Stack

- **MongoDB**: Document database for flexible data storage
- **Express.js**: Backend API framework
- **Node.js**: JavaScript runtime environment
- **Google Maps API**: For route calculations and address autocompletion
- **JWT**: For authentication and authorization

## Getting Started

### Prerequisites

- Node.js (latest LTS version)
- MongoDB
- Google Maps API key

### Installation

1. Clone the backend repository

   ```bash
   git clone https://github.com/marcelhess/mh-expenses-app-render-backend-v2.git
   cd mh-expenses-app-render-backend-v2
   ```

2. Install backend dependencies

   ```bash
   npm install
   ```

3. For the complete application, also clone and set up the frontend:

   ```bash
   git clone https://github.com/marcelhess/mh-expenses-app-render-frontend-v2.git
   cd mh-expenses-app-render-frontend-v2
   npm install
   ```

4. Configure backend environment variables
   Create a `.env` file in the backend root directory and add:

   ```env
   PORT=5000
   MONGODB_URI=<your-mongodb-uri>
   JWT_SECRET=<your-jwt-secret>
   GOOGLE_MAPS_API_KEY=<your-google-maps-api-key>
   GEMINI_API_KEY=<your-gemini-api-key>
   NODE_ENV=development
   ```

5. Start the backend development server
   ```bash
   npm run dev
   ```

   The backend API will be available at `http://localhost:5000`

6. Configure and start the frontend (in the frontend repository):
   ```bash
   # In the frontend directory
   npm run dev
   ```

   The frontend will be available at `http://localhost:5173`

## API Endpoints

- Authentication: `/api/auth`
- Users: `/api/users`
- Expenses: `/api/expenses`
- Categories: `/api/categories`
- Reports: `/api/reports`

## License

This project is for internal use only by AussenDienst GmbH.
# mh-expenses-app-render-backend-v2
