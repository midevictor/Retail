# Moniechoke Landing Page

[![Built with Next.js](https://img.shields.io/badge/Built%20with-Next.js-000000.svg)](https://nextjs.org/)
[![Deployed on Cloud Run](https://img.shields.io/badge/Deployed%20on-Google%20Cloud%20Run-4285F4.svg)](https://cloud.google.com/run)

## Table of Contents

- [About](#about)
- [Features](#features)
- [Live Demo](#live-demo)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running Locally](#running-locally)
- [Deployment](#deployment)
## About

This repository contains the source code for the official landing page of **Moniechoke**. The landing page serves as the primary introduction to the application, highlighting its key features, benefits, and calls to action for users to learn more or sign up.

It is built using the Next.js framework for a fast, SEO-friendly, and efficient user experience.

## Features

*   **[Describe Feature 1]:** e.g., Clear value proposition of the application.
*   **[Describe Feature 2]:** e.g., Highlights key benefits for users.
*   **[Describe Feature 3]:** e.g., Sections detailing specific features or use cases.
*   **[Describe Feature 4]:** e.g., Includes call-to-action buttons (e.g., Sign Up, Learn More).
*   **Responsive Design:** Optimized for display on various devices (desktop, tablet, mobile).
*   **Fast Loading:** Leverages Next.js optimizations for performance.
*   **SEO Friendly:** Structured for search engine visibility.

## Live Demo

Check out the live version of the landing page deployed on Google Cloud Run:

[**Live Site URL**](https://retail-766109226341.us-central1.run.app)

## Technologies Used

*   [Next.js](https://nextjs.org/) (React Framework)
*   [React](https://reactjs.org/) (JavaScript Library)
*   [Node.js](https://nodejs.org/) (Runtime Environment)
*   [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/) (Package Manager)
*   TypeScript
*   TailwindCSS
*   [Google Cloud Run](https://cloud.google.com/run) (Deployment Platform)
*   Google Cloud Build (CI/CD Pipeline)

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following installed:

*   Node.js (LTS version recommended)
*   npm or yarn

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/midevictor/Retail.git
    ```
2.  Navigate into the project directory:
    ```bash
    cd Retail
    ```
3.  Install dependencies:
    ```bash
    npm install
    # or
    yarn install
    ```

### Running Locally

To start the development server:

```bash
npm run dev
# or
yarn dev
```

Open [```

## Deployment

This landing page is automatically deployed to Google Cloud Run.

- **Trigger:** Deployment is triggered automatically by pushes or merges to the master branch of this repository.
- **Process:**
    1. A push/merge occurs on the master branch.

    2. Google Cloud Build trigger is activated.

    3. The application is built using a Buildpacks into a container image.

    4. The new container image is deployed to the configured Google Cloud Run service.

    5. The new version of the landing page becomes live at the Cloud Run service URL.

    6. No manual steps are required for deployment after merging changes into master.