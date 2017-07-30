### React-With-Flow-Test
A simple project for me to practice setting up Create React app with Flow typing.

## How I Did It

Here are the steps I took to set up this project.

1) Scaffolded a new React app with create-react-app.

`create-react-app react-with-flow`

2) Install bablel packages to deal with flow.

`npm install --save-dev babel-cli babel-preset-flow`

3) add .babelrc file to root of project.

`{
   "presets": ["flow"]
 }`

4) Tell Webstorm that you want to use Flow.

 Webstorm -> Preferences -> Languages And Tools -> JavaScript -> Choose "Flow" from dropdown.

5) Enjoy nice, strict typing in your IDE while running the dev server as usual.

`npms start`

Happy coding!