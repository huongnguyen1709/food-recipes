# food-recipes-responsive-UI

This is a responsive UI made from using TailwindCSS

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
   <li><a href="#prerequisites">Prerequisites</a></li>
   <li><a href="#quick-start">Quick start</a></li>
   <li><a href="#deployment">Deployment</a></li>
   <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## Prerequisites

- npm
  ```sh
  npm install npm@latest -g
  ```

## 🚀 Quick start

1.  **Step 1.**
    Clone the project
    ```sh
    # clone the project to your local computer
    git clone https://github.com/huongnguyen1709/food-recipes.git
    ```
1.  **Step 2.**
    Install NPM packages
    ```sh
    # It will install required dependencies and devDependencies for the project
    npm install
    ```
1.  **Step 3.**
    Build & Watch TailwindCSS file into your CSS file

    ```sh
    npm run build-css
    ```

1.  **Step 4.**
    Install live-server globally if you don't have it yet

    ```sh
    # Install it globally
    npm install live server -g
    ```

1.  **Step 5.**
    Start the project
    ```sh
    # Go to public folder and run:
    live-server
    ```

## 🚀 Deployment

Deploy the project as a Github Page

1.  **Step 1.**
    Install _gh-pages_
    ```sh
    # Install as a devDependency
    npm install gh-pages --save-dev
    ```
1.  **Step 2.**
    Add homepage url to package.json
    ```sh
    # In the package.json, add the homepage in the beginning, replace the URL with your Github-pages-link
    "homepage": "https://huongnguyen1709.github.io/food-recipes",
    ```
1.  **Step 3.**
    Add script _"deploy"_ to package.json

    ```sh
    # public folder where the html file is located in and it's gonna be public on Github page
    "scripts": {
        "deploy": "gh-pages -d public"
    },
    ```

1.  **Step 4.**
    Deploy _public_ folder to _gh-pages_ branch

    ```sh
    npm run deploy
    ```

1.  **Step 5.**
    Choose branch to be built for the Github Page

    - Go to setting -> Pages
    - Choose the branch to be built for the Github Page is _gh-pages_ -> press _save_
    - The site will be ready in minutes:
      - https://huongnguyen1709.github.io/food-recipes

## Acknowledgments

- [TailwindCSS Documentation](https://v2.tailwindcss.com/docs)
- [Heroicons - by the makers of TailwindCSS](https://heroicons.com/)
- [Google Fonts](https://fonts.google.com/)
- [Github Pages](https://pages.github.com/)
