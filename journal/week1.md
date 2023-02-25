# Week 1 — App Containerization

# Summary (skip to Details section below if already read on student portal)

## 1. Done (Homework)
- Finished everything within the checklist. 
- Submitted the 2 quizes on time. 
- Further details are explained within the student log (Student journal) for week-1

## 2. Done - Homework Challenges
- Expoloring other Cloud Environemnts
    - Researching OCI (Oracle Cloud Infrstrucutre) Application express & Open source CodeServer.

## 3. Problems
- Nothing Major. Some minor problems were faced but I managed my way to solve them.

## 4. What's next?
- Check if I can created another new AWS account instead of the blocked one in order to extend the free-tier. 
- Observaility (week 02).


# Details



### During Live Session

During week-1 live sesion, I managed to follow-up and do all the steps (with a slight delay). I managed to get both Containers for the backend flask webapp and the frontend React app about 1.5 hour after the live session.

Below are screen shots for the first run of crudder home page and signup page directly after the session
1. Crudder Home page ![Cudder home](week-01/crudder-home.png)
2. Crudder Signup page ![Sign up into Cudder](week-01/crudder-signup.png)


### Code Commit best practice

Concercing code commit, I already have my own best practices and thats why I commited my own code before watching Andrew's first video after the session reminding everyone to commit code before the environmnet is destroyed.


### Notfications feature
I watched the notification video and managed to add integrate the notification feature into both the frontend and backend. No major issues were faced.

Screen shots for notification feature:

1. Crudder Notifications from frontend
![Notifications - frontend](week-01/crudder-notifications-from-frontend.png)

2. Crudder Notifications (backend)

![Notifications - Backend](week-01/crudder-notifications-backend.png)



### Containerizing Databases (DynamoDB, Postgress) and installing AWS-CLI  on Gitpod

I followed the video and all went well.


Screen shots for adding the databases:

1. Installing Postgress on gitpod ![Installing Postgress on gitpod](week-01/installing-postgress-on-gitpod.png)

2. Installing aws-cli on gitpod ![Installing aws-cli on gitpod](week-01/installing-aws-cli-on-gitpod.png)

3. Ensure having both aws-cli and postgress in gitpod startup scripts ![aws-cli and postgress on gitpod startup](week-01/having-both-aws-cli-and-postgress-in-gitpod-startup-scripts.png)


4. Adding postgres to vscode extensions ![adding postgres to vscode extensions](week-01/adding-postgres-to-vscode-extensions.png)


After that I made two tests (one from the gitpos vscode terminal and the second from database explore) to ensure that postgress is working.

Screenshots are shown below:

1. Getting postgres to work as container from gitpod terminal ![postgre working as container from gitpod terminal](week-01/getting-postgres-to-work-as-container-from-gitpod-terminal.png)

2. Getting postgres to work as container from gitpod db explorer![postgre working as container from gitpod db explorer](week-01/testing-postgres-db-connection-from-db-explorer.png)

3. Sucessful connection from gitpod db explorer![Sucessful connection from gitpod db explorer](week-01/successful-postgres-connection-from-db-explorer.png)



### Playing around with Dynamo DB

I followed the video and all went well. The following screenshots shows 
- Table creation
- Creating item
- listing table
- Listing Music table



Screenshots for testing DynamoDB:

1. Table creation ![DynamoDB Table creation](week-01/dynamodb-testing-table-creation.png)

2. Item Creation ![DynamoDB Item Creation](week-01/dynamodb-testing-create-item.png)

3. Listing Table ![DynamoDB Listing Table](week-01/dynamodb-testing-list-table.png)

4. Listing Music Table ![Listing Table](week-01/dynamodb-testing-list-music-table.png)



