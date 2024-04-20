# Tailwind CSS Navigation Bar Project

This project is a simple navigation bar built using Tailwind CSS. It provides a clean and responsive navigation layout suitable for various web applications.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/): Download and install Node.js
- npm (Node Package Manager): This is installed automatically with Node.js

### Installing Tailwind CSS

1. First, create a new project directory and navigate into it:
   ```bash
   mkdir navigation-bar-project
   cd navigation-bar-project

2. Initialize a new npm project:
   ```bash
   npm init -y

3.  Install Tailwind CSS and its dependencies using npm:
    ```bash
    npm install tailwindcss postcss autoprefixer

4.  Create a Tailwind CSS configuration file:
    ```bash
    npx tailwindcss init

### Building the Project
1.Create an HTML file (index.html) in the root of your project directory.

2.Create a CSS file (styles.css) where you'll write your custom styles.

3.Import Tailwind CSS into your CSS file:
```css
   @import "tailwindcss/base";
   @import "tailwindcss/components";
   @import "tailwindcss/utilities";
```

4.Write your HTML markup and use Tailwind CSS classes to style your navigation bar.
5.Add a script in package.json to compile your CSS:
  ```json
"scripts": {
  "build-css": "tailwindcss build styles.css -o output.css"
}
```
6.Run the script to compile your CSS:
```bash
npm run build-css
```
7.Viewing the Project
You can view the project by opening the HTML file in a web browser. To streamline development, you can use a live server. 
Install live-server globally via npm or download Vs code extension


