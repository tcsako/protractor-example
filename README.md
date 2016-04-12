# protractor-example
Demo scripts for protractor

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
