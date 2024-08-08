
# Game Top-Up Website

This project is a game top-up website that allows users to top-up their accounts for games like Mobile Legends: Bang Bang and Call of Duty Mobile. It uses Stripe for payment processing and integrates with third-party services for delivering in-game credits.

## Project Structure

- **backend/**: Contains the backend code written in Node.js/Express.
- **frontend/**: Contains the frontend code written in React.

## Getting Started

### Backend

1. Navigate to the `backend` directory.
2. Install the dependencies: `npm install`
3. Create a `.env` file with your Stripe and third-party API keys.
4. Start the server: `npm start`

### Frontend

1. Navigate to the `frontend` directory.
2. Install the dependencies: `npm install`
3. Start the development server: `npm start`

## Deployment

- Deploy the backend and frontend using your preferred hosting services.

## Environment Variables

- `STRIPE_SECRET_KEY`: Your Stripe secret key.
- `THIRD_PARTY_API_KEY`: Your third-party API key for top-up services.
