# Steps to Fix Registration Issue

## 1. Install MongoDB Community Edition
- Go to https://www.mongodb.com/try/download/community
- Download the MSI installer for Windows.
- Run the installer and follow the prompts to install MongoDB.
- During installation, choose "Complete" setup type.
- Start the MongoDB service after installation.

## 2. Install MongoDB Compass
- Go to https://www.mongodb.com/try/download/compass
- Download and install MongoDB Compass.

## 3. Create Database using Compass
- Open MongoDB Compass.
- Connect to `mongodb://localhost:27017`
- Click on "Create Database"
- Database Name: `ecom`
- Collection Name: `users` (or leave default)
- Click Create.

## 4. Run the Backend Locally
- Open terminal in `d:/E Commerce FS/EcomProject/Backend`
- Run `npm install` to install dependencies.
- Run `node app.js` to start the server on port 5000.

## 5. Run the Frontend Locally
- Open another terminal in `d:/E Commerce FS/EcomProject/shop-frontend`
- Run `npm install`
- Run `npm run dev` to start the frontend (usually on http://localhost:5173)

## 6. Test Registration
- Open the frontend in browser.
- Go to register page.
- Try registering a new user.
- It should work now, as backend connects to local MongoDB.
