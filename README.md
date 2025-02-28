TMDB API Reference Documentation

## Project Overview
This project is my Capstone project for the Technical Writing Mentorship Program (TWMP) API Docs Cohort. It is a reference documentation for The Movie Database (TMDB) API, designed to help developers easily understand and utilize 100+ API endpoints for retrieving movie, TV show, and entertainment-related data.

## Project Steps
1. Setting Up TMDB API Access:
- Created an account on TMDB.
- Obtained the necessary credentials, including the API key.

## 2. Reviewing the TMDB API
- Conducted a thorough review of the official TMDB API documentation.
- Examined all available API endpoints to understand their functionality and use cases.

## 3. Testing API Endpoints
- Tested each TMDB API endpoint using Postman.
- Verified responses, checked for errors, and documented different request parameters, descriptions, and expected responses.

## 4. Documenting API Endpoints in Postman
- Created a structured Postman collection for TMDB API.
- Documented each endpoint, including:
- Request parameters
- Response formats
- Detailed descriptions

## 5. Transitioning to OpenAPI Specification
- Exported the documented API endpoints from Postman to an OpenAPI specification.
- Converted the JSON file to YAML using TWMP’s OpenAPI spec converter.
- Edited and refined the OpenAPI spec using Swagger Editor and VS Code.
- Conducted further testing to ensure accuracy.

## 6. Building Documentation with Mintlify
i. Signed up on Mintlify and linked my GitHub account.
ii. Started creating the API documentation on Mintlify, covering:
- Introduction
- Authentication
- How to obtain an API key
- API reference
- API essentials etc

- Customized the documentation’s look and feel using Mintlify components and custom CSS.

Installation & Setup

1. Clone the Repository
If this project is hosted on GitHub, you can clone it using:

```bash
   git clone https://github.com/your-username/tmdb-api-docs.git
cd tmdb-api-docs

```

2. Install Mintlify CLI (Optional for Local Development)
If you want to run the documentation locally, install the Mintlify CLI:

```bash
npm install -g mintlify

```

3. Start the Local Server
To preview the documentation locally, run:

```bash
mintlify dev

```

Then, open `http://localhost:3000` in your browser.

Conclusion
This documentation provides a well-structured, developer-friendly reference for the TMDB API, improving accessibility, usability, and overall user experience. 

Demo
You can view the live TMDB API documentation here:
[Live Documentation](https://rayoco.mintlify.app/introduction)