# SpicyNuggs

Spicy Nuggs is a modern e-commerce platform designed to provide a seamless and fun shopping experience. The platform aims to showcase the influencer’s unique personality while incorporating key e-commerce features:

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
  - [Issue Structure](#issue-structure)
  - [Branch Naming Convention](#branch-naming-convention)
- [License](#license)

## Project Overview

**SpicyNuggs** is a modern e-commerce platform, designed to offer customers a seamless and engaging shopping experience. The project will include:

- Product catalog with images and descriptions.
- Shopping cart and checkout functionality.
- User authentication and order tracking.
- Admin dashboard for managing products and orders.

## Technologies Used

This project uses the following stack:

- **Frontend**: React, SCSS
- **Backend**: Cloud Functions
- **Database**: FireStore
- **Deployment**: Firebase

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/) for dependency management

### Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/AnthonyQuispe/SpicyNuggs
   ```

2. Navigate into the project directory:

   ```bash
   cd SPICYNUGGS
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

## Folder Structure

The project follows this folder structure:

```
SPICYNUGGS/
│
├── public/                   # Public assets
├── src/
│   ├── components/           # React components
│   ├── pages/                # Pages for the e-commerce app
│   ├── assets/               # Images, icons, and other assets
│       ├── images/           # Images used in the project
│       ├── icons/            # SVG icons
│       ├── logos/            # SVG logos
│       ├── icons/            # SVG icons
│       ├── placeholders/     # placeholder imgs
│       ├── backgrounds/      # background imgs
│       ├── sounds/           # sounds files
│   └── styles/               # Global SCSS files
│       ├── partials/         # SCSS files

│
├── .gitignore                # Ignored files and folders for git
├── package.json              # Project dependencies and scripts
└── README.md                 # Project overview and contribution guidelines
```

## Contributing

We welcome contributions to SpicyNuggs Here are some guidelines for contributing to the project.

### Issue Structure

When creating an issue, please follow the structure below:

**Title:**

```
[Task Type] - [Component/Feature] - [Specific Action]
```

**Example:**

```
[Feature] - Product Page - Add image carousel
```

**Description:**

```
### Task Overview:
Briefly describe the task, what it involves, and its goal.

### Subtasks:
- [ ] Subtask 1
- [ ] Subtask 2

### Figma Links (if applicable):
[Link to Figma design](https://figma.com/example-link)

### Acceptance Criteria:
- What should be achieved once the task is complete.

### Dependencies:
- List any dependencies or tasks that need to be done before this one.

### Assigned:
```

### Labels:

- Use labels like `assets`, `feature`, `bug`, etc.

### Branch Naming Convention

To keep branches organized, we use the following naming convention when creating new branches:

```
[number][task-type]/[feature-or-component]
```

**Example:**

- `feature/product-page/add-carousel`
- `bugfix/footer/fix-broken-links`
- `design/header/update-logo`

Make sure to always start the branch name with the type of task (`feature`, `bugfix`, `design`, etc.), followed by the component or feature you’re working on, and a short description of the change.

### Pull Requests

- When submitting a pull request, link the relevant issue in the description.
- Ensure your branch is up to date with the `main` branch before submitting.

## License

This project is licensed under the MIT License.

---
