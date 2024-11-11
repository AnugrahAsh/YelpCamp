# YelpCamp

YelpCamp is a full-stack web application where users can create, view, and review campgrounds. It allows users to register, log in, add new campgrounds, and view details about campgrounds created by other users.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Future Improvements](#future-improvements)
- [License](#license)

## Project Overview

YelpCamp is a web application developed as a practice project to learn and implement full-stack web development with Node.js, Express, MongoDB, and Passport.js. It enables users to create and review campgrounds, enhancing their experience with a simple, user-friendly interface. User authentication is handled by Passport.js with sessions to maintain login state.

## Features

- **User Authentication**: Secure sign-up, login, and logout functionality using Passport.js.
- **Campground CRUD**: Create, Read, Update, and Delete operations for campgrounds.
- **Review System**: Users can add and delete reviews for campgrounds.
- **Flash Messages**: Provides feedback to users after certain actions (e.g., registration success, login errors).
- **Responsive Design**: A responsive, mobile-friendly layout.

## Technologies Used

- **Backend**: Node.js, Express
- **Authentication**: Passport.js with Passport-Local-Mongoose
- **Database**: MongoDB, Mongoose for MongoDB object modeling
- **Frontend**: HTML, CSS, Bootstrap, EJS templating engine
- **Flash Messages**: connect-flash for displaying success/error messages

## Installation

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/yelpcamp.git
    cd yelpcamp
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add your MongoDB connection string and session secret:
    ```plaintext
    DATABASE_URL=mongodb://localhost:27017/yelp_camp
    SESSION_SECRET=yourSecretHere
    ```

4. Start the application:
    ```bash
    node app.js
    ```

5. Visit the application at `http://localhost:3000`.

## Usage

- **Home Page**: Lists all campgrounds.
- **Register/Login**: New users can register; existing users can log in.
- **Add New Campground**: Users can add new campgrounds.
- **View Details**: Click on a campground to view its details and reviews.
- **Add/Edit/Delete Review**: Registered users can add, edit, or delete their own reviews.


## Future Improvements

- **Map Integration**: Integrate a map to display campground locations.
- **Search and Filtering**: Add search functionality to find campgrounds based on location, name, etc.
- **Enhanced UI/UX**: Improve the visual design and usability of the app.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
