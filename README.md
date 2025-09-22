# ChitChat  |  [live link](https://chitchat-frontend-rho.vercel.app/)

ChitChat is a full-stack real-time chat application built with React (Vite) for the frontend and Node.js/Express for the backend. It supports user authentication, real-time messaging, and user profile management.

## Features

- User authentication (login, registration)
- Real-time chat between users
- User profile management
- Responsive and modern UI
- Image and asset support

## Tech Stack

**Frontend:**
- React (Vite)
- Context API for state management
- CSS for styling

**Backend:**
- Node.js
- Express.js
- MongoDB (with Mongoose)
- JWT authentication
- Cloudinary for image uploads

## Project Structure

```
chitchat/
├── client/        # Frontend (React)
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   └── ...
│   ├── public/
│   └── ...
├── server/        # Backend (Node.js/Express)
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── ...
└── README.md
```

## Getting Started

### Prerequisites
- Node.js (v16+ recommended)
- npm or yarn
- MongoDB instance (local or cloud)

### Setup

#### 1. Clone the repository
```sh
git clone https://github.com/Tanmayasahoo3536/chitchat.git
cd chitchat
```

#### 2. Setup the backend
```sh
cd server
npm install
# Create a .env file with required environment variables (see .env.example if available)
npm start
```

#### 3. Setup the frontend
```sh
cd ../client
npm install
npm run dev
```

#### 4. Open the app
Visit `http://localhost:5173` (or the port shown in the terminal) in your browser.

## Environment Variables

Both `client` and `server` require `.env` files for configuration. Example variables:

**server/.env**
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_URL=your_cloudinary_url
```

**client/.env**
```
VITE_API_URL=http://localhost:5000
```

## Deployment

- The project includes `vercel.json` files for deployment on Vercel.
- Configure environment variables in your deployment dashboard.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Cloudinary](https://cloudinary.com/)
