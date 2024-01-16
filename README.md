# Strapi Test

## Description

This repository contains the backend for the Strapi Test project, powered by Strapi. It provides the necessary APIs and content management for the project.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed on your machine
- npm or yarn package manager installed

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/etharrra/strapi-test.git
   ```

2. Navigate to the project directory:

   ```bash
   cd strapi-test
   ```

3. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

## Configuration

1. Run the migration:

   ```bash
   npm run develop
   # or
   yarn develop
   ```

   This will run the Strapi development server and apply any database migrations.

## Usage

- Access the Strapi admin panel by navigating to `http://localhost:1337/admin`.
- Create and manage your content types, APIs, and configurations through the Strapi admin dashboard.

## API Endpoints

- All API endpoints are accessible under the base URL `http://localhost:1337`.

| Endpoint         | Description                              |
| ---------------- | ---------------------------------------- |
| `/landing-pages` | API endpoint for managing landing pages. |

## Acknowledgements

- [Strapi Documentation](https://strapi.io/documentation)
- [Coding After Thirty](https://www.youtube.com/watch?v=RceLeh9D85o)
