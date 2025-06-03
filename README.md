# YumYum Food Delivery Mobile App


## Overview

YumYum is a comprehensive food delivery mobile application built with React Native and Expo. The app provides a seamless experience for users to browse restaurants, order food, track deliveries in real-time, and make secure payments across both iOS and Android platforms.

## Features

- 📱 **Cross-platform support** for iOS and Android
- 🔍 **Restaurant browsing** with detailed menus and categories
- 🛒 **Cart management** with easy modification of items
- 💳 **Secure payment processing** using Stripe
- 📍 **Real-time order tracking** with map integration
- 👤 **User profiles** with order history and saved preferences
- 🔔 **Push notifications** for order status updates
- 📊 **Restaurant dashboard** for order management
- 📍 **Location-based discovery** to find nearby restaurants
- ⭐ **Ratings and reviews** for restaurants and dishes

## Tech Stack

- **Frontend**
  - [React Native](https://reactnative.dev/) - Mobile framework
  - [Expo](https://expo.dev/) - Development platform
  - [TypeScript](https://www.typescriptlang.org/) - Programming language
  - [Redux Toolkit](https://redux-toolkit.js.org/) - State management

- **Backend**
  - [Node.js](https://nodejs.org/) - Runtime environment
  - [Express.js](https://expressjs.com/) - Web framework
  - [MongoDB](https://www.mongodb.com/) - Database
  - [JWT](https://jwt.io/) - Authentication

- **Services & Integration**
  - [Firebase](https://firebase.google.com/) - Push notifications & storage
  - [Stripe](https://stripe.com/) - Payment processing
  - [Google Maps API](https://developers.google.com/maps) - Map integration



### Prerequisites
- Node.js (v14 or later)
- npm or Yarn
- Expo CLI
- MongoDB
- Firebase account
- Stripe account

### Mobile App Setup

1. Clone the repository
   ```bash
   git clone https://github.com/Mohamed-gp/YumYum.git
   cd YumYum
   ```

2. Install dependencies
   ```bash
   yarn install
   # or
   npm install
   ```

3. Start the development server
   ```bash
   yarn start
   # or
   npm start
   ```

## Project Structure

```
YumYum/
│
├── app/                # Main application code
│   ├── assets/         # Images, fonts, etc.
│   ├── components/     # Reusable UI components
│   ├── navigation/     # Navigation configuration
│   ├── screens/        # App screens
│   ├── services/       # API services
│   └── utils/          # Helper functions
│
├── server/             # Backend server code
│   ├── controllers/    # Request handlers
│   ├── models/         # MongoDB models
│   ├── routes/         # API routes
│   └── utils/          # Helper functions
│
├── app.json            # Expo configuration
├── package.json        # Dependencies and scripts
└── tsconfig.json       # TypeScript configuration
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ by [Mohamed Outerbah](https://github.com/Mohamed-gp)' > ~/Desktop/gm/mine/README_YumYum.md
