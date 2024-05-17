# Text-Editor

## Progressive Web Application (PWA) Text Editor

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Technical Criteria](#technical-criteria)
- [Deployment](#deployment)
- [Application Quality](#application-quality)
- [Repository Quality](#repository-quality)
- [License](#license)

## Description

This project is a Progressive Web Application (PWA) text editor designed to provide users with a reliable note-taking and code snippet management solution. The application features offline functionality, allowing users to create and access their content even without an internet connection. Data persistence is ensured through the use of IndexedDB, providing redundancy in case of network failures. Additionally, the application can be installed as a standalone PWA on supported devices, providing users with a seamless and immersive experience.

## Installation

1. Clone the repository:
   ``` bash
   
   git clone https://github.com/your-username/text-editor.git
   ```
2. Navigate to the project directory:
   ``` bash
   Copy code
   
   cd text-editor
   ```
3. Install dependencies:
   ```bash
   Copy code
   
   npm install
   ```
## Usage

1. Start the development server:
``` bash
Copy code

npm run start
```
2. Open your web browser and navigate to http://localhost:3000 to access the text editor application.
 
## Technologies Used

- Node.js
- Express.js
- React
- IndexedDB
- Workbox
- Webpack
- Babel

## Technical Criteria

  * Uses IndexedDB to create an object store and includes both GET and PUT methods

  * The application works without an internet connection

  * Automatically saves content inside the text editor when the DOM window is unfocused

  * Bundled with webpack

  * Create a service worker with workbox that Caches static assets

  * The application should use babel in order to use async / await

  * Application must have a generated `manifest.json` using the `WebpackPwaManifest` plug-in

  * Can be installed as a Progressive Web Application

## Deployment

* Application deployed to Render at live URL with build scripts

* Application loads with no errors

* Application GitHub URL submitted

* GitHub repo contains application code

## Application Quality

* Application user experience is intuitive and easy to navigate

* Application user interface style is clean and polished

* Application resembles the mock-up functionality provided in the Challenge instructions


## Repository Quality 

* Repository has a unique name

* Repository follows best practices for file structure and naming conventions

* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

* Repository contains multiple descriptive commit messages

* Repository contains quality README file with description, screenshot, and link to deployed application

## License

  This Text editor project is licensed under the MIT License.
  
  - **Your Name**: Hemalatha Prakasam
  - **GitHub**: [GitHub Profile](https://github.com/hemuprabu)


Feel free to copy and paste this Markdown code into your README.md file. You can customize it further according to your project's specific details and requirements. Let me know if you need any further assistance!


## Contact

If you have any feedback, questions, or suggestions regarding the Text Editor application, feel free to reach out to me:

- **Email**: Hemalathaprakasam219@gmail.com

I welcome any feedback or inquiries and am happy to assist with any queries related to the Text Editor project. Your input is valuable in improving the application and making it more user-friendly.

