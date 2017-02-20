Ref: https://www.youtube.com/watch?v=uextYhQGP6k

Steps to create ReactJS project from empty project e.g. ReactEnvironmentSetupProject like this one

Execute following command from project root directory

//Step 1 , initialize project using npm init that will update package.json with basic info
$ npm init
//Enter series of answer as appropriate e.g. project name , author , license etc or simple enter to leave default as is

//Step 2. install dependency that will require for the app . Here --save tell npm that these are production dependency
$ npm install react react-dom --save

//Step 3. install more dependecy for packaging, stand up service to serve reactjs files, transpiler ie. babel to trapile es6 to es5
$ npm install webpack webpack-dev-server babel-loader babel-preset-es2015 babel-preset-react babel-preset-stage-2 --save-dev

//Setp 4.
//Add webpack.config.js inside project root / src folder
