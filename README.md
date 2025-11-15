<<<<<<< HEAD
# 🧪 Restful Booker API Testing Project

<img src="https://assets.publish.postman.com/og-image?heading=WORKSPACE&entityName=Restful%20Booker%20Collections&entityType=workspace&imageUrl=https%3A%2F%2Fres.cloudinary.com%2Fpostman%2Fimage%2Fupload%2Ft_team_logo%2Fv1654544603%2Fteam%2F467456b12fa1769ff37861bdf99b338528f85a7c40135e85165ad6280dbd4a35.png&isVerified=false&teamName=Automation%20in%20Testing" alt="Restful Booker Logo" width="600"/>

## 📖 Introduction

This project is dedicated to testing the booking functionalities of the [Restful Booker API](https://restful-booker.herokuapp.com/apidoc/index.html).  
It serves as a practical exercise in API testing, focusing on creating, retrieving, updating, and deleting booking records.

## ✨ Features

- **Authentication**: Implement token-based authentication.
- **Create Booking**: Create new hotel bookings with customer details and stay information.
- **Retrieve Bookings**: Fetch all bookings or specific booking details.
- **Update Booking**: Modify existing booking information either fully or partially.
- **Delete Booking**: Remove a booking from the system.

## 🛠️ Installation

Follow these steps to set up the project locally:

1. **Install Node.js**  
   Download and install Node.js from the [official website](https://nodejs.org/).

2. **Install Newman and HTML Extra Reporter**  
   Open your terminal and run:

   ```bash
   npm install -g newman
   npm install -g newman-reporter-htmlextra

3. **Clone this repository:**

   ```bash
   git clone https://github.com/mabdel130/API-testing-Restful-Booker-Project.git
   ```

4. **Navigate to the project directory:**

   ```bash
   cd API-testing-Restful-Booker-Project
   ```

5. **Import the Postman collection and environment into Postman:**
   - Open Postman.
   - Import the provided `Restful-booker Project.postman_collection` and `Restful-booker_Testing.postman_environment` files.

## 🚀 Usage

You can run the tests in two ways:

### Option 1: Run manually from Postman
- Open Postman.
- Choose the imported collection.
- Select the correct environment.
- Click **Run** to execute the test cases manually.

### Option 2: Run automatically using `run.bat`
- Locate the `run.bat` file inside the project directory.
- Double-click the `run.bat` file to start running the tests.
- This will automatically:
  - Run the Postman collection using Newman.
  - Generate an **HTML report** inside the `newman/` folder.


## 📄 Notes

- After the test execution, an HTML report will be available in the `newman` folder.
- If you face permission issues, run the terminal or `.bat` file as an administrator.
=======
Api Testing 
>>>>>>> 03cf2b653d74205e448fe41b75c6f4a2bbd1133c
