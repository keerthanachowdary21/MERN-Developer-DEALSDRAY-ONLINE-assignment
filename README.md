# User Registration Form with MongoDB, Express, and Node.js

This is a basic **User Registration** form project using Node.js, Express, and MongoDB. 
The form allows users to submit their details such as name, email, phone number, gender, designation, and course selection. Upon submission, the data is stored in a MongoDB database.

### Registration Form
<div><img src='https://drive.google.com/uc?export=view&id=1RmICQncyfTLpeP-IOa_HD7okB-MtiSz4' alt='Registration Form output' /></div>

### Registration Form output
<div>
  <video width="640" height="360" controls>
    <source src="https://drive.google.com/uc?export=download&id=1qu36_jfeGy5wje1JDmdW2KPLR9hQ8fE9" type="video/mp4">
  </video>
</div>

  
## Features

- User can fill out a registration form with the following fields:
  - Full name
  - Email
  - Mobile number
  - Gender
  - Designation (HR, Manager, Sales)
  - Course (MCA, BCA, BSC)
  - File upload for photo
- Data is validated and sent to the MongoDB database.
- After successful submission, the user is redirected to a success page.
  
## Technologies Used

- **Node.js**: JavaScript runtime environment for backend logic.
- **Express**: Web framework for Node.js used to create the API endpoints.
- **MongoDB**: NoSQL database to store user data.
- **Mongoose**: ODM (Object Data Modeling) library for MongoDB.
- **Bootstrap**: CSS framework for responsive form design.
- **Body-parser**: Middleware for parsing form data.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (v18 or higher)
- [MongoDB](https://www.mongodb.com/) (Ensure MongoDB is running locally)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/user-form
    cd user-form
    ```

2. Install the necessary dependencies:

    ```bash
    npm install
    ```

3. Set up MongoDB:

    - Start your MongoDB server locally.
    - The database will be created automatically as you insert data.

### Running the Application

The application will be accessible at http://localhost:3000.

Routes
**GET /: Serves the registration form page.**

**POST /sign_up: Accepts the form data and inserts it into the MongoDB collection.**

