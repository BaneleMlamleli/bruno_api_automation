# ![bruno](./asset/bruno.png) Bruno_API_Automation

- This is an API testing project where I will be using [restful-booker](https://restful-booker.herokuapp.com/apidoc/index.html) for my REST API as it is well documented.
- The objective is to automate the test cases I have written to validate the end-points using the Chai library and to learn Bruno for future use.
- I also want to explore alternative API clients. I want something that allows me to use Git, not lock me into creating an account. Bruno is a Git-friendly and offline-first open-source API client, there's no logging into an account, and there is no cloud connection or syncing of the work you do in Bruno.

## Tech-stack for the project

- Bruno
- Bruno CLI (@usebruno/cli)
- NodeJS
- Chai Library

## Execution

You can execute the tests in two ways:

- Use Bruno CLI with HTML reports. Generate the reports into the /reports directory
  - bru run ./core/ --reporter-html ./reports/reports.html
- Install Bruno and run the folder, collection, or individual API calls
