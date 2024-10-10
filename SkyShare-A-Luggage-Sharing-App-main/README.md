SkyShare
Seamless Luggage Sharing for Air Travelers

SkyShare is an innovative mobile application that connects passengers traveling on the same flight to share luggage space. By optimizing baggage usage, SkyShare helps reduce baggage fees and maximize space efficiency. The platform ensures secure and efficient collaboration among travelers, offering significant savings in both space and costs.

Table of Contents
Project Overview
Technology Stack
Key Features
Directory Structure
Getting Started
Project Overview
SkyShare revolutionizes the way air travelers manage their luggage by enabling them to share unused baggage space with fellow passengers on the same flight. Key functionalities include:

Secure User Authentication: Ensures that only verified users can access the platform.
Real-Time Communication: Chat rooms facilitate seamless interaction between passengers.
Luggage Management: Users can post available luggage space or search for space offered by others.
In-App Wallet: Users can earn and manage earnings by sharing their luggage space.
Robust Data Handling: Efficiently stores and manages user, luggage, and flight information using MongoDB.
Technology Stack
Frontend: Flutter
Backend: Node.js, Express.js
Database: MongoDB
Authentication: JSON Web Tokens (JWT)
Key Features
User Authentication: Secure login and registration using JWT to protect user data.
Real-Time Chat Rooms: Enables passengers to communicate instantly for coordinating luggage sharing.
Luggage Posting & Browsing: Users can list their available luggage space or browse offers from others on the same flight.
In-App Wallet: Facilitates financial transactions, allowing users to earn money by sharing their unused luggage space.
Data Management: Utilizes MongoDB for storing and managing comprehensive data related to users, luggage, and flights.
Directory Structure
Frontend (Flutter)
android/: Android-specific code and configuration files.
ios/: iOS-specific code and configuration files.
lib/: Core Flutter application code.
main.dart: The main entry point of the Flutter app.
screens/: All UI screen components.
models/: Data models used within the app.
services/: API calls and other service-related functionalities.
widgets/: Reusable custom widgets.
assets/images/: Image assets utilized in the application.
linux/, macos/, windows/, web/: Platform-specific code and configurations.
Backend (Node.js)
server/: Backend server codebase.
index.js: Main entry point for the Node.js server.
routes/: Defines all API endpoints.
models/: Mongoose schemas for MongoDB collections.
controllers/: Functions handling API request logic.
middlewares/: Custom middleware functions for request processing.
test/: Test suites for ensuring backend reliability.
Getting Started
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/skyshare.git
cd skyshare
Frontend Setup:

Navigate to the Flutter project directory:
bash
Copy code
cd frontend
Install dependencies:
bash
Copy code
flutter pub get
Run the application:
bash
Copy code
flutter run
Backend Setup:

Navigate to the server directory:
bash
Copy code
cd server
Install dependencies:
bash
Copy code
npm install
Start the server:
bash
Copy code
npm start
Usage
Register or Log In:

Open the SkyShare app and sign up with your credentials or log in if you already have an account.
Manage Luggage:

Post Luggage Space: If you have extra luggage capacity, post the details to offer space to other passengers.
Search for Space: Browse available luggage spaces posted by other travelers on your flight.
Communicate:

Use the real-time chat feature to coordinate and finalize luggage sharing arrangements with other passengers.
Handle Earnings:

Manage and track your earnings through the integrated in-app wallet feature.
