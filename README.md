# Working Memory & Imagery Experiment Application

## Project Overview

This is a React-based web application designed for conducting working memory and imagery experiments. The application was built using Create React App and features a comprehensive experimental interface for Experiment 1.

## Repository

GitHub: [https://github.com/HaminNou/Nourbakhshi-Pourmirzaei-Cowan-2026](https://github.com/HaminNou/Nourbakhshi-Pourmirzaei-Cowan-2026)

---

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- **Node.js** (version 14.0 or higher recommended)
  - Download from: [https://nodejs.org/](https://nodejs.org/)
  - To check if installed: `node --version`

- **npm** (comes with Node.js) OR **yarn**
  - npm to check: `npm --version`
  - yarn to check: `yarn --version`

---

## Installation Instructions

### Step 1: Extract the Project

If you received this as a ZIP file, extract it to your desired location.

### Step 2: Open Terminal/Command Prompt

Navigate to the project directory:

```bash
cd quiz-app-react
```

(Or navigate to wherever you extracted the project)

### Step 3: Install Dependencies

You have two options:

**Option A: Using npm (recommended)**
```bash
npm install
```

**Option B: Using yarn**
```bash
yarn install
```

This will install all required packages listed in `package.json`. The installation may take several minutes.

---

## Running the Application

### Development Mode

After installation is complete, start the development server:

**Using npm:**
```bash
npm start
```

**Using yarn:**
```bash
yarn start
```

The application will automatically:
- Start the development server
- Open your default browser to [http://localhost:3000](http://localhost:3000)
- Enable hot-reload (the page reloads automatically when you make changes)

### Stopping the Server

To stop the development server:
- Press `Ctrl + C` in the terminal/command prompt
- Type `Y` when asked to confirm

---

## Available Scripts

### `npm start` or `yarn start`
Runs the app in development mode at [http://localhost:3000](http://localhost:3000)

### `npm test` or `yarn test`
Launches the test runner in interactive watch mode

### `npm run build` or `yarn build`
Builds the app for production to the `build` folder
- Optimized for best performance
- Minified and ready for deployment

### `npm run eject` or `yarn eject`
⚠️ **Warning**: This is a one-way operation. Only use if you need full control over build configuration.

---

## Project Structure

```
quiz-app-react/
├── public/                 # Static files
│   ├── index.html         # Main HTML file
│   └── ...
├── src/                   # Source code
│   ├── Components/        # React components
│   ├── pages/            # Page components
│   │   └── main/         # Main page (homepage)
│   ├── assets/           # Images and resources
│   ├── helpers/          # Utility functions
│   ├── layouts/          # Layout components
│   ├── modules/          # Experiment modules
│   ├── router/           # Routing configuration
│   ├── App.js            # Main App component
│   └── index.js          # Entry point
├── package.json          # Project dependencies
├── .gitignore           # Git ignore rules
└── README.md            # This file
```

---

## Features

- **Experiment 1**: Main experimental interface (accessible from homepage)
- Tutorial system
- Performance feedback
- Data collection and export

---

## Technical Details

### Built With
- **React** 17.0.1
- **React Router** 6.21.2
- **Material-UI (MUI)** 5.15.4
- **Redux** 4.0.5
- **Styled Components** 6.1.8

### Browser Compatibility
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

---

## Troubleshooting

### Issue: Port 3000 is already in use
**Solution**: Either:
1. Stop the other application using port 3000, or
2. The app will prompt you to use a different port (press Y)

### Issue: Module not found errors
**Solution**: Delete `node_modules` folder and `package-lock.json`, then run `npm install` again

### Issue: npm install fails
**Solution**: 
1. Ensure you have the latest Node.js version
2. Try clearing npm cache: `npm cache clean --force`
3. Delete `node_modules` and try again

### Issue: White screen on startup
**Solution**: 
1. Check browser console for errors (F12)
2. Ensure all dependencies installed correctly
3. Try clearing browser cache

---

## Important Notes

⚠️ **Node Modules**: This package does NOT include the `node_modules` folder. You MUST run `npm install` or `yarn install` before running the application.

⚠️ **Internet Connection**: An internet connection is required during the initial `npm install` to download dependencies.

⚠️ **Development vs Production**: The `npm start` command runs a development server. For production deployment, use `npm run build`.

---

## Support & Documentation

- **React Documentation**: [https://reactjs.org/docs/getting-started.html](https://reactjs.org/docs/getting-started.html)
- **Create React App Documentation**: [https://create-react-app.dev/](https://create-react-app.dev/)
- **Material-UI Documentation**: [https://mui.com/](https://mui.com/)

---

## Version

**Version**: 0.1.0

---

## License

This project is private and proprietary.

---

## Quick Start Summary

```bash
# 1. Navigate to project directory
cd quiz-app-react

# 2. Install dependencies
npm install

# 3. Start the application
npm start

# 4. Open browser to http://localhost:3000
```

That's it! The application should now be running successfully.

---

*Last Updated: November 2025*
