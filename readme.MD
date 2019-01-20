## Migrate MySQL users to MongoDB ##

### Prerequisites ###

    *  Python >= 3.7
    *  pipenv >= 2018.11.26
    *  MongoDB >= 3.6

### Installation ###

    * run `git clone https://github.com/samayamnag/icmyc-user-migration <projectname>` to clone the repository
    * run `cd <projectname>`
    * run `cp .env.example .env`
    * configure .env
    * run `pipenv shell --python=3.7` to set up environment. --python argument is optional. This is to       specify specific python version 
    * run `pipenv install` to install dependencies

### Run the Application


```sh
$ python migrate.py
```
