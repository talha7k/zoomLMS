# Zoom Clone

## 📋 Table of Contents
- [Zoom Clone](#zoom-clone)
  - [📋 Table of Contents](#-table-of-contents)
  - [🤖 Introduction](#-introduction)
  - [⚙️ Tech Stack](#️-tech-stack)
  - [🔋 Features](#-features)
  - [🤸 Quick Start](#-quick-start)
    - [Prerequisites](#prerequisites)
    - [Cloning the Repository](#cloning-the-repository)
    - [Installation](#installation)
    - [Set Up Environment Variables](#set-up-environment-variables)
    - [Running the Project](#running-the-project)
  - [🚀 More](#-more)
  - [📬 Contact](#-contact)
  - [📄 License](#-license)

## 🤖 Introduction
Built with the latest Next.js and TypeScript, this project replicates Zoom, a widely used video conferencing tool. It enables users to securely log in, create meetings, and access various meeting functionalities such as recording, screen sharing, and managing participants. The application leverages modern web technologies to deliver a seamless and secure video conferencing experience.

For a step-by-step guide to building this project, check out our accompanying tutorial [link to be added]. If you need assistance or encounter any bugs, feel free to reach out to the project maintainer.

## ⚙️ Tech Stack
- **Next.js**: React framework for server-side rendering and static site generation.
- **TypeScript**: Typed JavaScript for enhanced code reliability.
- **Clerk**: Authentication and user management platform.
- **GetStream**: Real-time API for video and chat functionalities.
- **TanStack Query**: Data fetching and state management for seamless API interactions.
- **Shadcn UI**: Reusable UI components for rapid development.
- **Tailwind CSS**: Utility-first CSS framework for responsive styling.

## 🔋 Features
- **👉 Authentication**: Secure login via Clerk with social sign-on or email/password, ensuring proper access control.
- **👉 New Meeting**: Start meetings quickly, with options to configure camera and microphone settings.
- **👉 Meeting Controls**: Full control over meetings, including recording, emoji reactions, screen sharing, muting/unmuting, sound adjustments, grid layout, participant list view, and individual participant management (pinning, muting, unmuting, blocking, video sharing).
- **👉 Exit Meeting**: Participants can leave meetings, and creators can end meetings for all attendees.
- **👉 Schedule Future Meetings**: Schedule meetings with date and time, accessible via the "Upcoming Meetings" page for sharing or starting instantly.
- **👉 Past Meetings List**: View details and metadata of previously held meetings.
- **👉 View Recorded Meetings**: Access recordings of past meetings for review.
- **👉 Personal Room**: Unique, shareable meeting link for instant meetings.
- **👉 Join Meetings via Link**: Easily join meetings created by others using a provided link.
- **👉 Secure Real-time Functionality**: All interactions are secure and occur in real-time, prioritizing user privacy and data integrity.
- **👉 Responsive Design**: Seamlessly adapts to various screen sizes and devices.
- **And more**: Well-structured code architecture and reusable components for maintainability.

## 🤸 Quick Start
Follow these steps to set up the project locally on your machine.

### Prerequisites
Ensure you have the following installed:
- Git
- Node.js
- npm (Node Package Manager)

### Cloning the Repository
```bash
git clone https://github.com/talha7k/zoom-clone.git
```

### Installation
Install the project dependencies using npm:
```bash
npm install
```

### Set Up Environment Variables
Create a `.env` file in the root of your project and add the following content:
```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```
Replace placeholder values with your actual Clerk and GetStream credentials. Obtain these from the [Clerk website](https://clerk.com) and [GetStream website](https://getstream.io).

### Running the Project
```bash
npm run dev
```
Open `http://localhost:3000` in your browser to view the project.

## 🚀 More
- **Code Architecture**: Organized for scalability and reusability, leveraging Next.js app router and TypeScript.
- **Data Fetching**: Powered by TanStack Query for efficient and cached API requests.
- **Community Support**: Reach out to the maintainer for help or to report issues.

## 📬 Contact
For questions or feedback, reach out to:
- **Name**: Talha Khan
- **Email**: talha7k@gmail.com
- **Phone**: 442-421-5593
- **Website**: https://dijitize.com

## 📄 License
This project is licensed under the MIT License.