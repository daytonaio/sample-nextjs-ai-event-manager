# Sample TS/NextJS

![home](https://github.com/user-attachments/assets/dfb10eaf-c687-4743-a450-fbe28920373c)
![events](https://github.com/user-attachments/assets/ee6e26ef-700c-4e2b-8372-1b1fddbd7944)


## Table of Contents

- [COOPER WORD](#cooper-word)
  - [Getting Started](#getting-started)   
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Features](#features)
  - [Tech Stack](#tech-stack)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)
  - [How to Contribute](#how-to-contribute)
  - [Contributors](#contributors)
  - [Contact](#contact)

## 🚀 Getting Started

 ### Open Using Daytona
 
 1. **Install Daytona**: Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/).
 
 2. **Create the Workspace**:
 
    ```bash
    daytona create https://github.com/daytonaio/sample-nextjs-ai-event-manager.git
    ```
 3. To start the IDE:
    ```
    daytona code 
    ```
    
 4. Select Linux as the machine
 
 5. Add .env.local file in root with:
    ```
    GROQ_API_KEY=""
    CLERK_SECRET_KEY=""
    COPILOTKIT_PUBLIC_KEY=""
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=""
    NEXT_PUBLIC_CLERK_SIGN_IN_URL=""
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=""
    RESEND_API_KEY=""
    ```
   
 6. **Start the Application**:
    ```bash
    npm run dev
    ```


## Overview

The **COOPER WORD** is a web-based tool designed to help users create, manage, and view events in a calendar format. Built using **React**, **Next.js**, and **TypeScript**, this application provides a user-friendly interface with intuitive functionality for effective event management.

## Demo Part 1 & 2

[![DEMO VIDEO](https://img.youtube.com/vi/Z5wQipy6GjU/0.jpg)](https://www.youtube.com/watch?v=Z5wQipy6GjU)

[![Demo video](https://img.youtube.com/vi/SRBzNzywWY4/0.jpg)](https://youtu.be/SRBzNzywWY4?si=4OJ1oZoYrgo4rmgu)

## Features

- **Interactive Calendar**: Navigate through months and select specific dates to view or add events easily.
- **Add New Events**: Click on any date to open a modal dialog and input details for new events, including:
  - **Title**: The name of the event.
  - **Date**: When the event occurs.
  - **Time**: The time the event starts.
  - **Priority**: Categorize events as High, Medium, or Low.
  - **Description**: Additional details about the event.
- **Event Details View**: Click on existing events to view detailed information in a dialog.
- **Priority Color Coding**: Events are visually categorized by priority, using distinct colors for easy identification.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Tech Stack

- **Frontend**:
  - **React**: A JavaScript library for building user interfaces.
  - **Next.js**: A React framework for server-side rendering and generating static websites.
  - **TypeScript**: A typed superset of JavaScript that compiles to plain JavaScript.
  - **Tailwind CSS**: A utility-first CSS framework for styling.
  - **React Icons**: A collection of beautiful SVG icons for use in React applications.
  - **ShadCn Hexta Ui**: A component library used in for Ui.
  - **Resend Email**: used for sending emails with reminder

## Usage

- **Navigating the Calendar**: Use the arrow buttons to switch between months.
- **Adding Events**: Click on a date to open the "Add Event" dialog. Fill in the event details and click "Add Event" or use the copilotkit chat to make it easier to add the events.
- **Viewing Event Details**: Click on any event bubble on the calendar to open the "Event Details" dialog.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please follow these steps:

1. **Fork the repository**.
2. **Create a new branch** for your feature or bug fix:
   `bash
   git checkout -b feature/YourFeature
   `

3. **Make your changes** and commit them:
   `bash
   git commit -m 'Add some feature'
   `

4. **Push to the branch**:
   `bash
   git push origin feature/YourFeature`

5. **Open a pull request** to the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by various event management solutions available online.
- Thanks to the contributors of libraries and tools used in this project.

## How to Contribute

Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for detailed information on how to contribute to this project.

## Contributors

Thanks to the contributors who have helped make this project better. Contributions of any kind are welcome!

## Contact

If you have any questions or feedback, feel free to reach out to me at github , email , instagram.
