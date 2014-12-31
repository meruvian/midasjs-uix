Getting Started to Using MidasJS
=======


Anyway, MidasJS is an integrated library related to create a HTML5 dynamic page, and we use AngularJS, Bower, Grunt to run it.

To start workaround with MidasJS, follow these steps:

You must install 
- nodejs
- npm
- bower
- grunt-cli

We use Ubuntu, and these are the steps to start install the components:

- sudo apt-get install nodejs npm
- sudo npm install -g npm
- sudo npm install -g bower grunt-cli


- git clone https://github.com/meruvian/midasjs.git
- cd midasjs
- npm install
- bower install

- grunt serve


Build Project: 
# grunt build
 
The project will be compiled and the compiled will be put inside folder /dist
- copy file images from /app/images to  /dist/images
- copy font from /bower_components/font-awesome/fonts to /dist/fonts


