## BDD and Test Automation

This is the template code and readme for the NTD2013 workshop by Mati Parv.

The application that we will use in the workshop's hands-on section is available at http://ntd2013-workshop.herokuapp.com

### Set up environment

The workshop is presented on a Mac OS X system, but everything shown should work without major changes on Linux and Windows computers as well. As many operations take place on the command line, Windows users are encouraged to use something else than Command Prompt. A good choice is *git bash*, which is installed with Git for Windows and becomes available in the right-click menu.

In the workshop it is assumed participants are comfortable installing software packages on their computers and can set up the environment described below on their own.


The following is the minimum software required for the workshop:

* Ruby 1.9.3
    * OS X users have 1.8 installed by default, use rvm to upgrade - https://rvm.io
    * Linux users should use their package managing systems to install Ruby, e.g. apt-get install ruby1.9
    * Windows users should install Ruby 1.9.3 from http://rubyinstaller.org and Ruby Devkit from http://rubyinstaller.org/add-ons/devkit
* Rubygems
    * Install from http://rubygems.org/pages/download
    * Note: Windows Ruby installer comes with Rubygems already included
* Firefox - this is the browser used by Selenium-Webdriver by default. It is also possible to use Chrome (with chromedriver), but doing so is not within the scope of this guide.
* A text editor of your choice. Workshop is presented using TextMate, but any decent editor will work.


The following gems should be installed (use 'gem install gemname' to install):

* rspec
* capybara
* selenium-webdriver


### Get and run test code template

To get the code template for the workshop, clone or download this repository. Instructions are available at the top of the page.

Open a shell in the folder where you downloaded the repository and execute the following command:

`rspec spec`

The application under test is opened in a new browser window and you will see the example test case (or scenario, as it is called in ) executing, after which the result is displayed in the shell prompt.
