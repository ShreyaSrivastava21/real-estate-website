# real-estate-website


---

# real-estate-website

## Project Overview

Homiyz is a modern real estate platform built using the MERN stack. It offers users the ability to browse, list, and manage property listings with an integrated authentication system. The project incorporates user authentication  and Google authentication using Firebase.

## Authors
   **Training project (Batch-1)**

- **Sparsh Dixit**
  - Course: BCA 
  - Semester: 4th
  - Section : B
  - Roll No:47
  - Email: sparshd02@gmail.com
  
- **Shreya Srivastava**
   - Course: BCA
   - Semester: 4th
   - Section : B
  - Roll No:44
  - Email: shreya.21.srivastava.12@gmail.com

## Features

- User authentication 
- Google authentication via jWT
- Create, read and delete property listings
- Responsive and user-friendly UI
- State management with Redux Toolkit

## Technology Stack

- **Frontend:**
  - React-VITE
  - Redux Toolkit
  - CSS 
  
  

- **Backend:**
  - Node.js
  - Express.js
  - cors
  - dotenv
  - mongoose
  - bcrypt
  - jsonwebtoken
  - nodemom

- **Database:**
  - MongoDB Atlas
  - prisma

  - **Cloud**
  -Cloudinary

- **Authentication:**
  - Custom User Authentication (JWT)

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm or yarn
- MongoDB
- cloudinary account

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rishabhgupta2004/HOMEHEAVEN.git
   cd homeheaven
   git clone https://github.com/Deepanshishukla24/HOMEHEAVEN.git
   ```

2. Install the dependencies for both the client and server:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

3. Set up environment variables:

   Create a `.env` file in the `server` directory and add your mongo DB url and PORT:

   ```plaintext
   DATABASE_URL=your_Database_URL
   PORT =your localhost for backend
   ```


### Running the Application

1. Start the backend server:
   ```bash
   cd server
   npm start
   ```

2. Start the frontend development server:
   ```bash
   cd client
   npm run dev
   ```

3. Open your browser and navigate to `http://localhost:5173` to see the application in action.

## Contributing

We welcome contributions to Homiyz! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request

