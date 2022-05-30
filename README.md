# server-deployment-practice

1. Create a new repository in GitHub called server-deployment-practice.
2. Select the "Add a README".
3. in option "Add a .gitignore" chose Node.js.
4. in option "Choose a license" chose MIT license.
5. Clone the repo to your local machine.
6. Immediately create a "dev" branch to do your work in git checkout -b dev.

## Heroku

---

1. Create a new Heroku app, called anas-server-deploy-dev:-

- Connect the app to this repository Choose the "dev" branch.

2. Create a new Heroku app, called anas-server-deploy-prod :-

- Connect to the app your repository Choose the “main” branch.

## The Code

---

1. Initialize my app : – npm init -y.
2. Install your dependencies : – npm install dotenv express jest.
3. Create the files and folders : src / middelware / handlers / server.js / index.js ..etc.
4. Test server : – npm test.
5. Start server :– nodemon.

## Deploy to Dev

---

1. ACP on dev branch.
2. after we check it passing all test Open a pull request from dev to main merge this branch Once the tests pass.
3. Heroku will deploymy “main” branch to my “production” app!.
