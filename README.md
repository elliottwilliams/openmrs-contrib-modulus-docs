openmrs-contrib-modulus-docs
============================

API Documentation for [Modulus](https://github.com/openmrs/openmrs-contrib-moulus), the OpenMRS Modules directory

**[Browse the API Docs](https://openmrs.github.io/openmrs-contrib-modulus/)**

Changing the docs
-----------------

1. Clone this repo and install the [Grunt](http://gruntjs.com) CLI:

        git clone https://github.com/elliottwilliams/openmrs-contrib-modulus-docs.git
        cd openmrs-contrib-modulus-docs
        npm install -g grunt-cli          # Install the `grunt` command
        npm install                       # Install dependencies to build the docs
      
2. Edit the docs. Follow the [API Blueprint 1A specification](https://github.com/apiaryio/api-blueprint/blob/master/API%20Blueprint%20Specification.md).

    - If you'd like, you can fork this repo and use the online editor at [apiary.io](https://apiary.io) to edit the
    docs. However, this editor will only touch the `apiary.apib` file and you'll have to "un-concat" it before you 
    submit a pull request 😝.

3. Run `grunt` in the project directory to build a new `index.html`. If you run `grunt serve`, Grunt will start a
   server on port 8084 (or whatever the `PORT` variable is set to) that live-reloads changes your docs. Neato!

4. Commit, push, and submit a pull request!
