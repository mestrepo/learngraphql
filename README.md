# SETUP

> Setting Up Meteor Project With GraphQL

    # 1. create a meteor project with DEFAULT package structure
    # https://docs.meteor.com/commandline.html#meteorcreate
    meteor create learngraphql   
    cd learngraphql
    
    meteor # --port PORT_NUMBER
    ## START OPTIONAL ##
    # install following if above resulting in errors # 
    meteor npm install --save @babel/runtime
    meteor update --patch
    ## END OPTIONAL ##
    
    # 2. install GraphQL in meteor project
    meteor add apollo
    meteor npm install --save apollo-server-express

> add the code needed to install project dependencies

    # 3. install GraphQL dependencies 
    meteor npm install --save graphql-iso-date
    meteor npm install --save sequelize
    meteor npm install --save node-fetch

> for mocking sql and functional programming respectively
> used to insert mocking data

    # 4. install mocking package
    meteor npm install --save casual 
    
    # 5. install functional programming package
    meteor npm install --save lodash 
    
    #6. install other dependencies
    meteor npm install --save graphql
    meteor npm install --save sqlite3

> run app
    
    meteor


# EXAMPLE QUERIES
[Sample Create Read Update Delete graphQL operations](imports/api/CRUD_examples.txt)