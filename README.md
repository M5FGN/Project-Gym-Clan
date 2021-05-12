# Project Gym Clan


## Project Brief

A local gym has asked you to build a piece of software to help them to manage memberships and register members for classes.
  

## Important Information

This repo is a clone of [codeclan_project_gymclan](https://github.com/M5FGN/codeclan_project_gymclan) as of 10/4/21. codeclan_project_gymclan is being used for submission on PDA Software Development award so no further changes will be made to that repo. All updates and enhancements will be added to this repo instead. Refer to codeclan_project_gymclan repo to see the first stages of work on this project.

## Technologies Used

* Python
* Flask
* PostgresSQL
* HTML/CSS
  
## Instructions to View the App 

1. Pull Repo from GitHub

2. In the Terminal access the project's root folder - project-gym-clan.


3. Running the Database

```
createdb gymclan
```
```
psql -d gymclan -f db/gymclan.sql
```

4. Adding Seed Data to the database

```
python3 console.py
```

5. Running Flask

```
flask run
```

6. Viewing the Project in the Browser

In the browser navigate to url localhost:5000
