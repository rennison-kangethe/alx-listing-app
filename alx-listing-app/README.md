# ALX Listing App

## Description

The ALX Listing App project aims to scaffold and lay the foundational structure for a modern Airbnb clone. This initial milestone focuses on setting up a well-organized and scalable codebase using Next.js, TypeScript, TailwindCSS, and ESLint. By establishing a clean folder structure, reusable components, and adhering to best practices, the project ensures a solid starting point for building a dynamic, responsive, and user-friendly property listing page.

## Learning Objectives

- Gain hands-on experience scaffolding a Next.js project tailored for production readiness.
- Implement TypeScript for type safety and reusable interfaces to enhance code maintainability and robustness.
- Configure TailwindCSS for building responsive, accessible, and visually appealing UI components.
- Structure a Next.js project following industry-standard best practices, ensuring scalability and readability.
- Create foundational reusable components and organize assets effectively for real-world applications.

## Project Structure

- **components/common/Card.tsx:** This file will define a reusable Card component that will be used across the project to display information about various properties.
- **components/common/Button.tsx:** This file will define a reusable Button component, which will be used for actions like “Book Now,” “Details,” etc.
- **interfaces/index.ts:** Define all TypeScript interfaces related to the project. Start by creating placeholder interfaces for CardProps and ButtonProps.

* **constants/index.ts:** Set up constants to store any reusable data or strings such as API URLs, configuration settings, or UI text
* `styles/globals.css` – Global styles, includes Tailwind directives
* `tailwind.config.js` – Tailwind CSS configuration
* **public/assets/** – Static images and SVGs

## Setup & Run

1. Clone the repo: git clone https://github.com/<your-username>/alx-listing-app.git
2. Install dependencies: npm install
3. Run development server: `npm run dev`
4. Run development server: `npm run dev`

## Dependencies

- **Next.js** (v13+) for React-based web app
- **TypeScript** for type safety
- **TailwindCSS** for utility-first styling
- **ESLint** for code quality and consistency
