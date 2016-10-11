# EmberJS with Laravel API Project Walk-through 
This documentation will walk you through configuring a front-end web application and it's back-end API data resource. 

## Step 1: Clone Repositories
There are two repositories to download for our project - one for the front-end application and one for the back-end API.  

+ From your development folder, run the following to clone the project repositories:  
    * `git clone https://github.com/pitchinnate/tweeter.git` 
    * `git clone https://github.com/kuatsure/tweeter-client.git` 
    * You should now have two folders: 
    ~~~
       /tweeter 
       /tweeter-client 
    ~~~

## Step 2: Install requirements 

**Prerequisites** 
+ [Git](http://git-scm.com/)
+ [Node.js](http://nodejs.org/) (with NPM)
+ [Ember CLI](http://ember-cli.com/)
+ [Bower](http://bower.io/)
+ [PhantomJS](http://phantomjs.org/)

### MacOS 
For local development, we'll use **[Homebrew package manager](http://brew.sh/)** to install our dependancies. 
+ After **Homebrew** is installed, run the following from the `/tweeter-client` folder to make sure **brew** and **Node.js** are up-to-date: 
    * `brew update` 
    * `brew upgrade node`  
+ Install the **Ember CLI** (command line interface) 
    * `npm install -g ember-cli` 
+ Install and update **Bower**
    * `brew install bower` 
    * `bower update` 
+ Install and update **PhantomJS**
    * `brew install phantomjs` 
    * `brew upgrade phantomjs` 

### Windows 
+ [PuPHPet](https://puphpet.com/) 

- - -

## Step 3: Run the Ember Client
+ To make sure your Node dependencies are correct, purge the project `/node_modules` folder then refresh **Node** and **Bower** 
    * Delete the `/node_modules` folder
    * Run `node install`
    * Run `bower install`
+ You should now have a clean install and ready to run the Ember client. From the `/tweeter-client` folder, run
    * `ember serve` 
+ You should get the following messages: 
~~~
  Livereload server on http://localhost:49152 
  Serving on http://localhost:4200/ 
~~~
