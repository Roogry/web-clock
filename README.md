
# Web Clock

Displaying clock with date and time. This project was made as practicing webpack in "Belajar Fundamental Front-End Development" class by Dicoding



## Installation

Use web-clock with npm. after run script below, you can open index.html in /dist folder

```bash
  cd web-clock
  npm install
```
## Tech Stack

Loader
 - **css-loader** : handle loader for .css files
 - **style-loader** : use css as import in js file

Plugin
 - **HtmlWebpackPlugin** : for bundle html template with js bundle and give the result in ./dist
 - **webpack-dev-server** : auto rebuild webpack if there is any changed in project by run script npm run start-dev
 - **webpack-merge** : separate webpack config into dev and prod but with default config

