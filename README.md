API Automation - Contact List

This repository contains an automated API test suite using Postman for the Contact List API. The test collection is integrated with Jenkins using Newman, enabling automated execution in a CI/CD pipeline.


🚀 Features

Postman collection for Contact List API test scenarios.

Uses Newman for running tests from the command line.

Jenkins pipeline integration for automation.

HTML Extra Reporter for enhanced test report output.


🔧 Jenkins Integration Workflow

Jenkins pulls the latest repository.

Runs Postman collection using Newman.

Generates CLI and HTML reports.

[Optional] Pushes updated collection back to GitHub.

Jenkins Screenshot:
![image](https://github.com/user-attachments/assets/4c83fe12-1036-40d2-8676-3afe606f9ad7)
![image](https://github.com/user-attachments/assets/74a1d7e2-b80f-4b33-a6c6-208516c8745e)




🛠️ Prerequisites

Node.js installed

Newman installed globally:

npm install -g newman

Jenkins running with Git and Node.js plugins installed


🧪 How to Run Locally

Run the collection using:

newman run ContactList.postman_collection.json --reporters cli,htmlextra

To install the HTML Extra Reporter:

npm install -g newman-reporter-htmlextra


📂 Folder Structure

- contactList.postman_collection.json
- contactList.environment.json
- README.md
- /screenshots


🤝 Contributing

Feel free to fork this repository, make improvements, and submit pull requests.


🙋‍♀️ Author

Created by Ivy Delos Reyes

