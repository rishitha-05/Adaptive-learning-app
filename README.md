## Description and title 
   It is an online adaptive learning education platform which test the knowledge of student and recommend him the essential material

# Getting Started with My Project
   I have used the ReactJs for the frontend and backend was done with Flask

   React app can be created with the help of
   # command
   npx create-react-app myapp
## Installation

To get started with this project, you'll need to follow these steps:

1. *Install Python*: Ensure you have Python installed on your system. You can download Python from the official website: [Python Downloads](https://www.python.org/downloads/)

2. *Install Flask*: This project requires Flask. You can install Flask using: pip install Flask

3. *Install google.generativeai*: This project also requires google.generativeai. You can install it using: pip install google.generativeai


## how to work with google ai studio
   To get started with Google AI Studio, follow these steps:
   1. Sign Up or Log In: If you haven't already, sign up for a Google account or log in to your existing account.
   2. Access Google AI Studio: Visit the Google AI Studio website.
   3. Start a New Project: Click on the "Start a new project" button and follow the prompts to create a new project.

   Once you have set up your project in Google AI Studio, you can start using it for various machine learning tasks. Here are some common tasks and how to perform them:

   1. Create a New Notebook: Click on the "New notebook" button to create a new notebook. Choose the desired runtime environment (e.g., Python 3,  TensorFlow, PyTorch) and start writing your code.
   2. Import Data: Use the provided interface to import datasets or connect to external data sources.
   3. Run Code: Write your machine learning code in the notebook cells and run them to train models, perform analysis, or generate predictions.
   4. Collaborate: Share your notebooks with collaborators or work on them together in real-time.

## Steps to run the project
  # prerequisites 
      1. Visual Studio Code: Make sure you have Visual Studio Code installed on your system. You can download it from the official website.
      2. Node.js and npm: Ensure that Node.js and npm (Node Package Manager) are installed on your system. You can download and install Node.js from the official website.
      3. Python: Install Python on your system. You can download Python from the official website.
   # Setting up the Flask Backend
     mkdir my-flask-react-project
     cd my-flask-react-project
   # create variable environment
     python3 -m venv venv
     source venv/bin/activate 
     pip install Flask
     touch server.py
   # Setting up the React Frontend 
     cd my-flask-react-project
     npx create-react-app frontend
     cd frontend
     npm start
   #  Integrating React with Flask
      1. Ensure that your Flask app serves the React build files. You can do this by setting up Flask to serve the static files generated by React.
      2. Update your Flask routes to serve the React index.html file for all routes except API routes. 

   # Running Both Projects in Visual Studio Code
     1. npm start 
     2. python server.py



   #Github repository
 (https://github.com/rishitha-05/Adaptive-learning-app/)"# Adaptive-learning-app" 
 client(master branch)
 server(main branch)
"# Adaptive-learning-app" 
