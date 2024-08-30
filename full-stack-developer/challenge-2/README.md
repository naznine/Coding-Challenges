## Challenge 2: Multi-language Content Management System (CMS) API

### Scenario:
You're building a CMS for a news website that publishes articles in both Bangla and English. The CMS needs to handle content in both languages and provide appropriate APIs for the front-end to consume.

### Task:
Develop a Node.js/Express.js API that:
1. Allows creating, reading, updating, and deleting (CRUD) articles in both Bangla and English
2. Implements proper Unicode handling for Bangla text
3. Includes an endpoint for fetching articles with language filtering
4. Implements basic authentication for CMS users
5. Includes input validation and sanitization to prevent common security issues

### Technical Requirements:
- Use Node.js and Express.js for the API
- Use MongoDB for the database (you can use Mongoose as an ODM if you prefer)
- Implement JWT for authentication
- Use proper error handling and status codes
- Include unit tests for at least two critical endpoints

### Expected Output:
A fully functional Express.js application with defined routes, controllers, and models. Include a README with setup instructions and API documentation.