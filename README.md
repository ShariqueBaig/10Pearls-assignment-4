# Assignment 4 – API Testing with Postman

This repository contains the solution for Assignment 4 of the 10 Pearls Internship program. The goal of this project was to demonstrate proficiency in API testing using Postman, including dynamic variable handling, scripting, and API chaining.

## Project Overview
The collection tests the `https://api.restful-api.dev` service, performing a full CRUD (Create, Read, Update, Delete) lifecycle on objects.

### Features Included:
- **Full HTTP Methods**: GET, POST, PUT, PATCH, and DELETE.
- **Dynamic Data**: Pre-request scripts to generate random product names and prices.
- **API Chaining**: The `id` from the POST response is automatically captured and used for subsequent requests.
- **Variable Handling**: Uses collection-level variables for `baseUrl` and session-specific variables like `objectId`.
- **Comprehensive Assertions**: Chai-based tests for status codes, response structure, and data validation.
- **Intentional Failure**: Includes one failing test case in the PATCH request as per assignment requirements.

## Files
- `Assignment_4_Postman_Collection.json`: The exported Postman collection.

## How to Run
1. **Import the Collection**:
   - Open Postman.
   - Click the **Import** button.
   - Drag and drop the `Assignment_4_Postman_Collection.json` file into Postman.

2. **Run the Collection**:
   - Select the collection "Assignment 4 - API Testing with Postman, Sharique".
   - Click the **Run** button (Collection Runner).
   - Click **Run Assignment 4...**.

3. **Check Results**:
   - View the **Test Results** tab to see passing/failing assertions.
   - Open the **Postman Console** (`Ctrl+Alt+C`) to see the logged values and dynamic data.

## Technologies Used
- Postman
- JavaScript (Postman Sandbox)
- Chai Assertion Library
- RESTful API (https://restful-api.dev/)
