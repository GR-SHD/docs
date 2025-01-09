# Contributing to the SuperTokens Documentation

Thank you for your interest in contributing to the SuperTokens documentation!
This guide provides all the information needed to set up, build, and contribute effectively to this repository.

## Overview

The documentation project relies on the [Docusaurus](https://docusaurus.io/) framework to transform `MDX` files into an actual static website. MDX allows us to embed React components in the content, unlocking rich, interactive documentation experiences.

That being said, there are several things that are added on top of the Docusaurus utilities in order to adjust the tooling to our needs.
Those are presented throughout this document.

## How to run the project

### Prerequisites

To work with the documentation project locally, ensure you have the following tools installed:

- [Node.js](https://nodejs.org/en/download/) (version 18 or higher)

### Setup Steps

1. Install the dependencies:

```bash
npm install
```

2. Start the development server:

```bash
npm run start
```

## Project Structure

The two main directories where you will work are:

- `docs`: This is where the actual content sits. All the `.mdx` files are located here.
- `src`: This is where you will find the React components and the custom logic used in the website's functionality.

Below is a breakdown of the main directories and files in the project:

```
├── docs                     # The place where all the content lives
│   ├── _templates           # Templates that can be used as a starting point for new docs
│   ├── _blocks              # Add reusable mdx blocks here or in any other docs folder (based on who needs that abstraction)
│   └── [section-name]
│       └── _category_.json  # The project uses file based routing and each subfolder has this file to name and order it in the sidebar
├── src                      # The business logic of the website
│   ├── components
│   ├── context
│   ├── css
│   ├── hooks
│   ├── lib
│   ├── plugins              # Plugins used by docusaurus during the build process
│   └── theme                # Docusaurus components that get adjusted by us
├── scripts                  #
├── sidebars.ts
└── docusaurus.config.ts
```

### Routing

## How to add changes

### Code Style

### Writing Components

### Styling Guidelines

### Writing Guidelines

## How to test your code

### Validating code blocks
