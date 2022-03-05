# README-Generator

### 09 Node.js Homework: Professional README Generator

## Your Task

When creating an open source project on GitHub, it’s important to have a high-quality README for the app. This should include what the app is for, how to use the app, how to install it, how to report issues, and how to make contributions.

Your task is to write a program that quickly and easily creates a README file by using a command-line application to generate one. This allows the project creator to devote more time to working on the project.

The application will be invoked by using the following command:

```bash
node index.js
```

## User Story

```md
AS A developer
I WANT a README generator
SO THAT I can quickly create a professional README for a new project
```

## Acceptance Criteria

```md
GIVEN a command-line application that accepts user input
WHEN I am prompted for information about my application repository
THEN a high-quality, professional README.md is generated with the title of my project and sections entitled Description, Table of Contents, Installation, Usage, License, Contributing, Tests, and Questions
WHEN I enter my project title
THEN this is displayed as the title of the README
WHEN I enter a description, installation instructions, usage information, contribution guidelines, and test instructions
THEN this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests
WHEN I choose a license for my application from a list of options
THEN a badge for that license is added near the top of the README and a notice is added to the section of the README entitled License that explains which license the application is covered under
WHEN I enter my GitHub username
THEN this is added to the section of the README entitled Questions, with a link to my GitHub profile
WHEN I enter my email address
THEN this is added to the section of the README entitled Questions, with instructions on how to reach me with additional questions
WHEN I click on the links in the Table of Contents
THEN I am taken to the corresponding section of the README
```

## Review

The following are submitted for review:

- A walkthrough video demonstrating the functionality of the application.
  https://drive.google.com/file/d/1qihoc_euUy-E9QFmhOeKQ3Fosw210iAG/view

- A sample README.md file for a project repository generated using your application [Sample Screenshot](ScreenshotSample.png)

- The URL of the GitHub repository, with a unique name and a README describing the project
  https://github.com/tracyewilhelm/README-Generator
