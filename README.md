# PawFinds v2.0: A Pet Adoption System | MERN Stack Portfolio with JWT Auth, OTP Verification & Admin Panel
PawFinds is a website where users can either give a pet up for adoption or adopt one. The admin decides if a pet can be put up for adoption and reviews adoption applications. This new version includes JWT authentication, OTP verification, user profiles, and an enhanced admin dashboard with data visualization.

[Click to get older version PawFinds V1.0 ](https://github.com/KaShiekzmi/PawFinds-A-Pet-Adoption-System-MERN-Stack-Portfolio-with-Admin-Panel)

### Watch PawFinds in Action

[![Watch the video](https://github.com/KaShiekzmi/PawFinds-A-Pet-Adoption-System-MERN-Stack-Portfolio-with-Admin-Panel/assets/114513868/521826b2-10d9-41b4-aec3-3497e23d2cbb)](https://www.youtube.com/watch?v=wXQpAoX7_QY)

Click the image above to watch a demo of PawFinds on YouTube.


## Introduction
PawFinds connects pet lovers with pets in need of a home. This platform simplifies pet adoption with a user-friendly experience, now with enhanced security and functionality.

## New Features (V2.0)
 - JWT Authentication: Users are securely authenticated with JSON Web Tokens (JWT).
 - OTP Verification: Added extra security for users with one-time password (OTP) verification.
 - User Profiles: Each user now has a personalized profile where they can manage their information.
 - Admin Dashboard: A comprehensive dashboard with graphs showing the number of users registered and a pie chart displaying different types of pets available for adoption.

## General Features
- Users can submit a pet for adoption by filling out a form.
- Admin reviews adoption submissions and can approve or reject them.
- Approved pets are listed on PawFinds for potential adopters to view.
- Users interested in adopting a pet fill out an application form.
- Admin evaluates adoption applications to select the most suitable adopter.
- Admin maintains a history of adopted pets and their new owners.
- User can browse and search for available pets for adoption.
- They can filter pets based on pet type i.e. dog, cat, fish, etc.
- PawFinds offer detailed pet profiles with photos and descriptions.

## Technology Stack
PawFinds is built using the MERN stack (MongoDB, Express.js, React, Node.js) with added JWT authentication and OTP verification.

## **Please Note: This Project Is Designed for Laptop Screens**
Kindly be aware that this project is optimized for laptop screens and is not responsive for mobile or tablet devices.

## Installation
Follow these steps to set up the project locally:

1. Clone the repository: `git clone https://github.com/KaShiekzmi/PawFinds-v2.0-JWT-OTP-Admin-Dashboard.git`
2. Install dependencies: `npm install`
3. Create a .env file in the server directory with the following variables:
   - mongooseURL=mongodb+srv://username:password@cluster-url.mongodb.net/?retryWrites=true&w=majority&appName=pawfinds-pet-adoption-system
   - SECRET=your_jwt_secret_key
   - EMAIL_USER=your_email@example.com
   - EMAIL_APP_PASS=your_email_app_password
5. Run the server: `nodemon server` runs the server using nodemon, a tool that enhances the development experience by automatically restarting the server on file changes.
6. `npm start` to start front end.

### Additional Notes
- Ensure you have Node.js and npm installed on your machine.

## Contributing
We welcome contributions to improve PawFinds! To contribute, follow these steps:
- Fork the repository.
- Create a new branch: git checkout -b feature-new-feature
- Make your changes and commit them: git commit -m 'Add new feature'
- Push to the branch: git push origin feature-new-feature
- Create a pull request explaining your changes.

## Contact Information
For questions, please contact 
- [GitHub](https://github.com/kashiekzmi)
- [LinkedIn](https://www.linkedin.com/in/kashiekzmi)