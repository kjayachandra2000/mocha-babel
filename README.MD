# Babel setup for Mocha
### Summary
This directory consists on how to configure babel for Mocha

### Installation

node module installation of mocha

    npm i --save-dev mocha

node module installation of babel

    npm install --save-dev @babel/core @babel/cli @babel/preset-env @babel/register


### Configuring test

As per the documentation provided by babel, we have to use ```"test": "mocha --require babel-register"``` but this will not work. Instead of this we have to use ```"test": "mocha --require @babel/register"```

### Reference

babel --> https://babeljs.io/setup#installation

Mocha --> https://mochajs.org/