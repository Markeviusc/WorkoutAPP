This is a simple React application built using React Router and Material-UI components. It provides a basic structure for rendering different pages and includes a navigation bar and footer.

Installation

Clone the repository to your local machine.
Navigate to the project directory.
Run npm install to install the dependencies.
Usage

In the project directory, run npm start to start the development server.
Open your browser and visit http://localhost:3000 to see the app in action.
Components

App
The App component is the entry point of the application. It sets up the main layout using the Box component from Material-UI. It also includes the Navbar, Routes, and Footer components.

Navbar
The Navbar component renders a navigation bar at the top of the page. It provides links to the home page and exercise details page.

Routes
The Routes component from React Router is used to define the routes of the application. It renders different components based on the current URL path.

Home
The Home component is rendered when the URL path is /. It represents the home page of the application.

ExerciseDetail
The ExerciseDetail component is rendered when the URL path matches /exercise/:id. It represents the page for displaying details of a specific exercise. The :id parameter represents the unique identifier of the exercise.

Footer
The Footer component is displayed at the bottom of the page and provides additional information or links.

Customization

Feel free to customize the components, styles, and routes according to your application requirements. You can modify the existing components or create new ones to enhance the functionality and appearance of the app.
