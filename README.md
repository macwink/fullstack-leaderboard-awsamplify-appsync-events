# Amplify Leaderboard Overview

<img width="1509" alt="image" src="https://github.com/user-attachments/assets/379ad15f-d57a-46d2-9579-0e8d7594c734">

## Introduction

The Amplify Leaderboard is a web application that showcases the flexibility of Amplify Gen 2. It utilizes various AWS services and technologies to create a robust and scalable application.

## Getting Started

Clone this repository and install the dependencies:

```bash
npm install
```

To test the solution, use deploy your resources to AWS using sandbox:

```bash
npx ampx sandbox
```

Run the application in a seperate tab (keep the sandbox running):

```bash
npm run dev
```

## Technologies Used

- **Frontend**: The frontend is built using Amplify Gen 2, which leverages the AWS Amplify JavaScript libraries for authentication and API calls. The user interface is powered by ShadCN (Tailwind CSS) components, generated with V0 (a product of NextJS). NextJS is used to create a public home page and a protected admin section.
- **Backend**: Instead of AWS AppSync GraphQl, this uses IAM to sure an AWS AppSync Event API
- **Authentication**: The application uses Amazon Cognito for user authentication.

<img width="1174" alt="image" src="https://github.com/user-attachments/assets/2c544ab8-de13-413a-be36-c74deed3a68f">

## Features

The Amplify Leaderboard provides the following features:

1. **Amplify Gen 2 Integration**: The application showcases the flexibility of Amplify Gen 2, allowing developers to leverage AWS services while maintaining control over the infrastructure.
2. **ShadCN and V0 for UI**: The application uses ShadCN (Tailwind CSS) components, which were generated with V0 (a NextJS product), providing a modern and responsive user interface.
3. **NextJS for Frontend**: The application utilizes NextJS to create a public home page and a protected admin section, ensuring secure access to sensitive functionality.
4. **Amazon Cognito for Authentication**: The application leverages Amazon Cognito for user authentication, ensuring secure access to the application's features.
5. **Leaderboard API**: The application provides an API that allows users to list players, create new players, update player details, and delete players from the database.

## Contribution Guidelines

This application is open for contributions. Before submitting a pull request, please file an issue to discuss the proposed changes.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.
