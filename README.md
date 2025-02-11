# Online Grocery System 🛒  

Welcome to the **Online Grocery System** project! This is a full-stack web application developed as part of my senior project during my Bachelor’s degree in Computer Science at the **University of Central Missouri**. The application allows users to conveniently shop for groceries online, providing a seamless and responsive user experience.  

---

## Features  
- **User-Friendly Interface:** Intuitive design for easy navigation and shopping.  
- **Product Catalog:** Displays a wide range of grocery items with categories and filters.  
- **Shopping Cart:** Allows users to add, remove, and manage items before checkout.  
- **Responsive Design:** Optimized for both desktop and mobile devices.  
- **Secure Checkout:** Simulates a secure payment process for a complete shopping experience.  

---

## Technologies Used  
- **Frontend:** Angular, TypeScript, HTML, SCSS
- **Backend:** .NET C#
- **Database:** MongoDB
- **Version Control:** Git/GitHub
- **Tools:** Visual Studio Code, Docker

---

## Setup Instructions
**Prerequisites**
- Node.js (for Angular frontend)
- .NET SDK (for backend)
- MongoDB (for database)
- Docker (optional, for containerization)

---

**Step 1: Clone the Repository**

git clone https://github.com/[YourGitHubUsername]/Online-Grocery-System.git

cd Online-Grocery-System

**Step 2: Set Up the Backend**

 1. Navigate to the backend folder:
  cd backend
 2. Restore dependencies:
  dotnet restore
 3. Run the backend server:
  dotnet run

**Step 3: Set Up the Frontend**

 1. Navigate to the frontend folder:
    cd frontend
 2. Install dependencies:
    npm install
 3. Run the Angular development server:
    ng serve

**Step 4: Set Up the Database**

 1. Ensure MongoDB is installed and running.

 2. Update the connection string in the backend configuration file (appsettings.json) to point to your MongoDB instance.

**Step 5: Run with Docker (Optional)**

 1. Build the Docker images:
    docker-compose build

 2. Start the containers:
    docker-compose up

---

## Contributing

**Contributions are welcome! If you’d like to contribute to this project, please follow these steps:**

 1. Fork the repository.

 2. Create a new branch for your feature or bugfix.

 3. Commit your changes and push to the branch.

 4. Submit a pull request with a detailed description of your changes.

---

## Acknowledgments

 - University of Central Missouri for providing the opportunity to work on this project as part of my senior coursework.

 - My professors and peers for their guidance and feedback during the development process.
