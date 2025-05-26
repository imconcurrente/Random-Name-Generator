# Random-Name-Generator

### Description:
The Random Adjective-Noun Name Generator is a web application built using Node.js, Express, and EJS, aimed at generating random name combinations from predefined adjective and noun lists. This application demonstrates the use of various web development techniques and tools to create a dynamic and interactive user experience.

### Implementations:

1. **Project Initialization**:
    - **npm init**: Initializes a new Node.js project and creates a `package.json` file.
    - **npm install express body-parser ejs**: Installs the necessary packages for the project.

2. **Server Setup**:
    - **Express**: A web framework used to set up the server and handle routing.
    - **EJS**: A templating engine for rendering dynamic HTML pages.
    - **Body-Parser**: Middleware to parse incoming request bodies, particularly for form submissions.

3. **Static File Serving**:
    - Configured Express to serve static files from the `public` directory, allowing the inclusion of CSS and other assets.

4. **Dynamic Year in Footer**:
    - JavaScript is used to get the current year and pass it to the EJS template for display in the footer.

5. **Form Handling and Random Name Generation**:
    - **GET /**: Renders the initial page with the form.
    - **POST /generate**: Handles form submissions, randomly selects an adjective and a noun from predefined lists, and renders the result on the page.

6. **EJS Templates**:
    - Templates are used to include common header and footer partials and dynamically display the generated names.

### Code Breakdown:
- **app.js**: Main server file that sets up routes, middleware, and static file serving.
- **public/**: Directory for static files like CSS.
- **views/**: Directory for EJS templates including the main page (`index.ejs`) and partials (`header.ejs` and `footer.ejs`).
- **styles.css**: Defines the styling for the application, ensuring a responsive and visually appealing design.

### Usage:
1. **Install Dependencies**: `npm install`
2. **Start the Server**: `node app.js`
3. **Access the App**: Navigate to `http://localhost:3000` to use the random name generator.

The app features a clean, responsive design and a user-friendly interface, showcasing fundamental web development practices and dynamic content rendering.
