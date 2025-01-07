# Ayur Leaf

Ayur Leaf is a modern e-commerce web application built using the MERN stack. It provides a platform for users to explore and purchase Ayurvedic products, read blogs, and manage their shopping cart. The project emphasizes a clean and intuitive user interface, offering a seamless user experience.

## Features

- **Home Page**: A modern and visually appealing landing page showcasing Ayurvedic products.
- **Blog Page**: Users can explore informative blogs about Ayurveda and health tips.
- **Shop Page**: A well-structured shop interface for browsing and purchasing products.
- **Cart Page**: Users can manage their selected products in the cart.
- **Authentication**: Login and signup functionalities for secure user access.
- **Chatbot**: A non-AI-powered chatbot to assist users.
- **Themes**: Option to switch between different themes.

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Styling**: Tailwind CSS for modern and responsive design

## Installation and Setup

To run this project locally, follow these steps:

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running locally or accessible via a cloud service

### Clone the Repository

```bash
git clone https://github.com/yourusername/ayur-leaf.git
cd ayur-leaf
```

### Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd frontend
npm install
```

### Environment Variables

Create a `.env` file in the `backend` folder and add the following:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### Run the Application

#### Start Backend Server

```bash
cd backend
npm start
```

#### Start Frontend Server

```bash
cd frontend
npm start
```

### Access the Application

Open your browser and go to `http://localhost:3000` to view the application.

## Project Highlights

- **Modern Design**: The UI is crafted with a focus on user-friendliness and aesthetics.
- **Scalable Architecture**: Backend and frontend are designed to support future enhancements.
- **Chatbot Integration**: Simplifies user interaction with the platform.

## Future Enhancements

- Implement a fully functional chatbot using AI/ML.
- Add payment gateway integration for seamless transactions.
- Expand backend features to support order tracking and user profiles.

## License

This project is licensed under the MIT License.

## Acknowledgments

- The MERN stack community for providing excellent tools and resources.
- Inspiration from modern e-commerce platforms for design and functionality.

---

Feel free to contribute to this project by submitting pull requests or reporting issues!
