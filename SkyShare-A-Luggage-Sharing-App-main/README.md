
# SkyShare-Seamless Luggage Sharing for Air Travelers

SkyShare is a mobile app designed to help air travelers share luggage space with others on the same flight. By connecting passengers, it allows those with extra luggage capacity to offer space to others, reducing baggage fees and optimizing the use of available luggage. The app provides secure user authentication, real-time chat for coordination, and an in-app wallet to manage earnings from shared luggage. With features like luggage posting and searching, SkyShare makes air travel more economical and efficient for its users.


## Tech Stack

Frontend: Flutter

Backend: Node.js, Express.js

Database: MongoDB

Authentication: JWT (JSON Web Tokens)


## Features

- User Authentication
- Real-Time Chat Rooms
- Luggage Posting & Browsing
- In-App Wallet
- Data Management


## Project Structure

## Frontend (Flutter)
- android/: Android-specific code and configuration files.
- ios/: iOS-specific code and configuration files.
- lib/: Core Flutter application code.
- main.dart: Entry point of the Flutter app.
  - screens/: UI screens.
  - models/: Data models.
  - services/: API calls and functionality services.
  - widgets/: Custom reusable widgets.
- assets/images/: Image assets for the app.
- linux/, macos/, windows/, web/: Platform-specific code and configurations.
## Backend (Node.js)
- server/: Backend codebase.
  - index.js: Entry point for the Node.js server.
  - routes/: API endpoints definitions.
  - models/: Mongoose schemas for MongoDB.
  - controllers/: Functions handling API logic.
  - middlewares/: Custom middleware for request handling.
  - test/: Backend test files for ensuring stability.








## Getting Started
## Installation

Clone the Repository:

```bash
  git clone https://github.com/yourusername/skyshare.git
  cd skyshare
```
Frontend Setup:

Navigate to the Flutter project directory:

```bash
  cd frontend
```
Install dependencies:

```bash
  flutter pub get
```
Run the application:

```bash
  flutter run
```
Backend Setup:

Navigate to the server directory:

```bash
  cd server
```
Install dependencies:

```bash
  npm install
```
Start the server:

```bash
  npm start
```



## Usage

## Register or Log In:

- Open the SkyShare app and sign up with your credentials or log in if you already have an account.
## Manage Luggage:

- Post Luggage Space: If you have extra luggage capacity, post the details to offer space to other passengers.
- Search for Space: Browse available luggage spaces posted by other travelers on your flight.
## Communicate:

- Use the real-time chat feature to coordinate and finalize luggage sharing arrangements with other passengers.
## Handle Earnings:

- Manage and track your earnings through the integrated in-app wallet featur

