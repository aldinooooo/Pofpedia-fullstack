
# Pofpedia - Fullstack Project

**Pofpedia** is a full-stack web application that allows users to browse, search, and interact with content in a user-friendly interface. The project demonstrates proficiency in both frontend and backend development, combining modern technologies to deliver a dynamic and responsive user experience.

## Features

- **User Authentication**: Secure registration and login functionality using JWT (JSON Web Token).
- **Search and Browse**: Users can search through content and browse items by category or keyword.
- **Dynamic Content Rendering**: Data is fetched from the backend and displayed dynamically on the frontend using React.
- **CRUD Operations**: Users can create, read, update, and delete content within the platform.
- **Responsive Design**: Fully responsive layout, ensuring a seamless experience across devices.
  
## Tech Stack

### Backend
- **Node.js**: Server-side runtime environment.
- **Express.js**: Web framework for building APIs.
- **MongoDB**: NoSQL database for managing data.
- **Mongoose**: ODM (Object Data Modeling) library for MongoDB and Node.js.
- **JWT**: Secure token-based authentication.
  
### Frontend
- **React.js**: JavaScript library for building user interfaces.
- **Redux**: State management for managing the app’s state globally.
- **CSS/SCSS**: Styling the frontend for a responsive and visually appealing design.

## Installation and Setup

To get started with the project, follow these steps:

### Prerequisites
Ensure you have the following installed:
- Node.js
- MongoDB
- Git

### Steps
1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/aldinooooo/Pofpedia-fullstack.git
   \`\`\`
2. Navigate to the project directory:
   \`\`\`bash
   cd Pofpedia-fullstack
   \`\`\`
3. Install the dependencies for both frontend and backend:
   \`\`\`bash
   cd backend
   npm install
   cd ../frontend
   npm install
   \`\`\`
4. Set up environment variables. Create a `.env` file in the backend directory with the following:
   \`\`\`bash
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   \`\`\`
5. Start the development server:
   - For the backend, navigate to the backend folder and run:
     \`\`\`bash
     npm run dev
     \`\`\`
   - For the frontend, navigate to the frontend folder and run:
     \`\`\`bash
     npm start
     \`\`\`

## API Endpoints

### User Authentication
- **POST** `/api/users/register`: Register a new user.
- **POST** `/api/users/login`: Authenticate user and return a token.

### Content Management
- **GET** `/api/content`: Get all content.
- **POST** `/api/content`: Create new content.
- **PUT** `/api/content/:id`: Update existing content by ID.
- **DELETE** `/api/content/:id`: Delete content by ID.

## Contributing

Contributions are welcome! If you have any ideas or improvements, feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License.
