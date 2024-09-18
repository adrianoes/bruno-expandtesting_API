# bruno-expandtesting_API

API testing in [expandtesting](https://practice.expandtesting.com/notes/api/api-docs/). This project contains basic examples on how to use Bruno to test API. All the necessary support documentation to develop this project is placed here.

# Pre-requirements:

| Requirement                     | Version        | Note                                                            |
| :------------------------------ |:---------------| :-------------------------------------------------------------- |
| Node.js                         | 18.18.0        | -                                                               |
| Bruno                           | 1.29.0         | -                                                               |
| Bruno CLI                       | 1.29.0         | -                                                               |

# Installation:

- See [Node.js page](https://nodejs.org/en) and install the aforementioned Node.js version. Keep all the preferenced options as they are.
- See [Bruno page](https://www.usebruno.com/downloads), download and intall it. 
- Open the project folder in terminal and execute ```npm install -g @usebruno/cli``` to install Bruno CLI.

# Tests:

- Execute ```bru run --env expandtesting_env --output ./reports/report.json``` to run the expandtesting.json collection configured with the expandtesting_env.bru environment variable file via command line and have the report inside reports folder.
- Execute ```bru run --env expandtesting_env``` to run the expandtesting.json collection configured with the expandtesting_env.bru environment variable file via command line and have the results on terminal.

# Support:

- [expandtesting API documentation page](https://practice.expandtesting.com/notes/api/api-docs/)
- [expandtesting API demonstration page](https://www.youtube.com/watch?v=bQYvS6EEBZc)
- [Bruno CLI](https://docs.usebruno.com/bru-cli/overview)

# Tips:

- UI and API tests to send password reset link to user's email and API tests to verify a password reset token and reset a user's password must be tested manually as they rely on e-mail verification.

