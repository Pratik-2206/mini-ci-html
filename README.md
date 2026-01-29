Mini HTML CI Project
This project demonstrates a simple Continuous Integration (CI) setup using GitHub Actions to validate an HTML file automatically.

Project Description:-
The repository contains a basic HTML file and a GitHub Actions workflow.
Whenever code is pushed to the main branch, the workflow runs and checks whether the HTML file follows correct HTML standards.

Tools and Technologies:-
-HTML5
-GitHub Actions
-html-validator-cli

How the CI Works:-
-A push is made to the main branch
-GitHub Actions starts automatically
-The workflow installs an HTML validator
-index.html is validated
-The build passes or fails based on HTML correctness

Project Structure:-
mini-ci-html/
├── index.html
├── README.md
└── .github/
    └── workflows/
        └── html-ci.yml

How to Use:-
-Edit the index.html file
-Commit and push the changes to main
-Open the Actions tab to see the CI result

Outcome:-
-Successful workflow run means the HTML is valid
-Failed workflow run indicates HTML errors

Author:-
Pratik-2206
