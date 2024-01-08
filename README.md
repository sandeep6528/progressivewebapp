Text Editor Web Application Readme

Overview
This application is a robust text editor built for the web, designed to provide a seamless experience for users in managing and editing text files. It features a client-server folder structure, leveraging modern web technologies to ensure a smooth and responsive user experience.

Getting Started
Folder Structure

Upon opening the application in your preferred editor, you'll find a clear client-server folder structure to manage both frontend and backend aspects of the app.
Starting the Application

Run npm run start from the root directory to initiate the backend and serve the client, enabling you to interact with the application.
Webpack Bundling and Plugins
Webpack Integration

JavaScript files are bundled using webpack to optimize performance and streamline code organization.
Webpack Plugins

Running webpack plugins generates essential files like HTML, a service worker, and a manifest file, enhancing the application's functionality and offline capabilities.
Advanced JavaScript and Functionality
Next-Gen JavaScript

The application supports next-generation JavaScript features while ensuring seamless functionality in the browser without encountering errors.
IndexedDB Integration

Upon opening the text editor, IndexedDB immediately creates a database storage, enabling seamless content saving and retrieval.
Content Persistence

Entered content is automatically saved using IndexedDB when clicking off the DOM window, ensuring that your work is preserved.
Persistence Across Sessions

Closing and reopening the text editor retrieves the previously saved content from IndexedDB, providing a consistent user experience.
Progressive Web App Features
Install Functionality

By clicking the "Install" button, you can download the web application as an icon on your desktop for quick access.
Service Worker and Workbox

The web application comes with a registered service worker using Workbox, facilitating offline access and improved performance.
Caching of Assets

Static assets are pre-cached upon loading, ensuring faster subsequent page loads and a seamless user experience.
Deployment and Build Scripts
Render Deployment
Proper build scripts tailored for a webpack application ensure seamless deployment to Render or similar platforms.
