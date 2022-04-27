# ADES_Assignment_Yr2

# what is gitignore? 
gitignore file is the file to ignore the files you dont want others to see (eg. ignore the env file as env file is the place you put some secret like db password, also like ignore node_modules as once run npm install we can get it, package json )


## Setup
1. Setup `.env` file.

    Create a new file `.env` in the root directory with the following content:

    ```
    DATABASE_URL=<DATABASE_URL>
    ```

    > Replace `<DATABASE_URL>` with the connection string to a PostgreSql database (e.g. `DATABASE_URL=postgres://username:password@host.elephantsql.com/user`)
    >
    > You can register for a free database instance (No credit card required) at [ElephantSql.com](https://www.elephantsql.com)
    >
    > ![elephantsql connection string](https://marcopeg.com/content/images/2021/11/image-33.png)
