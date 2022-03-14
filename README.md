# Neora Starter files (Foundation ^6)
---
## Basic starter files for Neora content with gulp/sass/foundation

1. Before you can get this running on your machine, you'll need to install some packages globally.
    - `npm install -g yo`

        This will install the yeoman generator package globally on your machine.

    - `npm install -g generator-neora-starter`

        This will install the package globally so you have access to it whenever you want locally.

2. Open a new project/directory and run `npm install neora-starter`. You should see your project fill up with the following files:
        
        1. frontend (folder)
        2. _gitignore
        3. .gitignore
        4. gulpfile.js
        5. index.html
        6. package-lock.json
        7. package.json
        8. README.md

3. Once you have all of your files and folders in your project, open the terminal (make sure you're in the root directory) and run `npm start`. This will download all dependencies needed to run the project (gulp, sass, & browsersync. As well as your minifiers). You should see your browser open up with a blank document. And that's it. Begin working in the `./frontend/src` directory and your changes will automatically get compiled upon save.
---

Going forward, you only have to run `npm install neora-starter` when you're ready to create a new project. You only need to install the global packages the first time.