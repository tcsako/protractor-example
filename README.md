# protractor-example
Demo scripts for protractor

Project setup:
1) Install NodeJS - https://nodejs.org/en/download/
2) Install protractor NodeJS package:
In your command line type the following npm command:
npm install -g protractor
3) Update your Selenium WebDriver
In your command line type the following:
webdriver-manager update
4) Start a standalone Selenium Server:
In your command line type the following:
webdriver-manager start
5) Start your script:
In your command line type the following:
protractor conf.js


spec.js - basic test scripts for an AngularJS based calculator
thomascook_spec.js - basic test scripts for https://www.thomascook.com/ an AngularJS based website
conf.js - basic configuration

In conf JS you can change the test script file:
specs: ['jetblue_spec.js']
or
specs: ['thomascook_spec.js'],

and the browser:
  capabilities: {
    'browserName': 'firefox'
  }
or
  capabilities: {
    'browserName': 'chrome'
  }
