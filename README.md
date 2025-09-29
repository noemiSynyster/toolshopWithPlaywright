# Toolshop with Playwright
This is a personal project where I used a prebuilt web project (not my authory) for creating an automated test suit using Playwright and implementing CI/CD pipeline to ensure the tests are running correctly when a user does a push to the repository.
I also created a document with test cases planned for this automated suite.

# Installation

Follow the steps to install it in your local:
- create a folder in your pc
- in VS Code enter to that folder
- then in terminal type: git clone git@github.com:noemiSynyster/toolshopWithPlaywright.git
- then enter the folder in terminal with: cd <folder_name>
- now install Playwright in the project: npm init playwright@latest
- select the following options in the console:
  ✔ Do you want to use TypeScript or JavaScript? · TypeScript
  ✔ Where to put your end-to-end tests? · tests
  ✔ Add a GitHub Actions workflow? (Y/n) · true
  ✔ Install Playwright browsers (can be done manually via 'npx playwright install')? (Y/n) · true
- Now project is installed
