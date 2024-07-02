# React Quiz App

This is a dynamic and interactive quiz app built with React, leveraging the `useReducer` hook for efficient state management. The app offers a user-friendly interface for taking quizzes on various topics and is designed to be responsive and provide smooth user interactions. It features 15 questions per quiz and displays the answers for user review.

## Functionality
- **Variety of Topics:** Users can choose from a variety of quiz topics.
- **Dynamic Question Handling:** Each quiz dynamically loads questions and answers.
- **State Management:** Utilizes the `useReducer` hook for managing quiz state, including current question, selected answers, and score, ensuring a more organized and scalable state management solution.
- **Immediate Feedback:** Users receive immediate feedback on their answers.
- **Score Calculation:** The app calculates and displays the user's score at the end of the quiz.
- **Responsive Design:** Compatible with various screen sizes for accessibility on desktop and mobile devices.
- **Progress Tracking:** Users can see their progress throughout the quiz.
- **Restart Option:** Users can restart the quiz at any time.

## Built With
- **HTML**
- **CSS**
  - Flex
  - Grid CSS
- **React**
  - `useReducer` for managing state

## Usage

### Prerequisites
Make sure you have Node.js and npm installed. If not, you can download and install them from [here](https://nodejs.org/).

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Saurabhraj2002/React_Quiz
   
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

### Running the App
1. **Start the development server:**
   ```bash
   npm start
   ```
   Open [http://localhost:3000](http://localhost:3000) to view it in the browser. The page will reload if you make edits.

### Building for Production
1. **Create a production build:**
   ```bash
   npm run build
   ```
   This will build the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance.

### Deployment
1. **Serve the production build locally:**
   ```bash
   npm install -g serve
   serve -s build
   ```
   Open [http://localhost:5000](http://localhost:5000) to view the production build.

2. **Deploy to GitHub Pages:**
   ```bash
   npm install gh-pages --save-dev
   ```
   Add the following scripts to your `package.json`:
   ```json
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d build"
   }
   ```
   Then deploy:
   ```bash
   npm run deploy
   ```

## Contributing
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

---

Feel free to customize further based on your project's specifics.
