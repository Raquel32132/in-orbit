# in.orbit
This is a simple server application built with NodeJS to manage goals. This is a project from NLW pocket for study purposes.

---

## Getting Started
To get started with this project, simply clone or download the repository and run 'npm install' to install the required dependencies. You can then start the server by running 'npm run dev'.

## Routes

#### Create Goal Completion
- **Endpoint:** `/completions`
- **Method:** `POST`
- **Description:** Creates a goal completion based on the provided `goalId`.
- **Request Body:**
  
  ```json
  {
    "goalId": "string"
  }
  ```

#### Create Goal
- **Endpoint:** `/goals`
- **Method:** `POST`
- **Description:** Creates a new goal with the given title and desired weekly frequency.
- **Request Body:**
  
  ```json
  {
    "title": "string",
    "desiredWeeklyFrequency": 1 // (integer, between 1 and 7)
  }
  ```

#### Get Pending Goals
- **Endpoint:** `/pending-goals`
- **Method:** `GET`
- **Description:** Returns the goals pending for the week.

#### Get Weekly Summary
- **Endpoint:** `/summary`
- **Method:** `GET`
- **Description:** Returns a summary of the goals for the week.

## Technology
- NodeJS
- API REST concepts
- Typescript
- Fastify
- DrizzleORM integration
- Insomnia
- Docker
- Zod for data validation

---

Made with ❤️ by Raquel Ramos Backes
 
