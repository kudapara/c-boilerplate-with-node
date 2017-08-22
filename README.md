# C Boilerplate using node

This project aims to make my life easier by taking advantage of npm scropts to compile my c application. At this stage it is very simple and basic but in the future I hope to place more features with your help of course.

## Getting started

This boiler plate works if you have [nodejs](http://nodejs.org) and [npm](http://npmjs.com) installed.

The ```main.c``` is the entry point of the application and the name ```main.c``` should not be changed because it the name that is recognised in the build scripts. However if you wish to change the name also update scripts in ```package.json``` for the program to continue working as expected.

### How to run

So in the terminal run the following:

**To compile**
```bash
  $ npm run build
```

**To run the compiled program**
```bash
  $ npm run run
```

**To compile and run using one command**
```bash
  $ npm run dev
```

## Licence

This project is free and open source and licenced under the MIT licence.