# space-trivia-games
Week 1-2: Project Setup and Initial Integration
Day 1-2: Initialize Project
Set Up GitHub Repository
Create a GitHub account (if you don't have one).
Create a new repository named space-trivia-game.
Clone the repository to your local machine:
Initialize React App
Install Node.js from nodejs.org.
Initialize a new React project:
Set Up Node.js and Express Backend
Initialize a new Node.js project and install Express:
Create a basic Express server in server/index.js:
Update GitHub with server setup:
Day 3-5: NASA API Integration
Obtain NASA API Key
Sign up for an API key from NASA API Portal.
Fetch Data from NASA APIs
APOD API: Fetch daily astronomy pictures.
Mars Rover Photos API: Fetch photos from Mars rovers.
Document API Integration
Create a docs directory in your repository.
Add API_Integration.md with details of how each API is used and example responses.
Day 6-10: Backend Development
Set Up Routes for APIs
Create routes in server/index.js for each NASA API.
Update GitHub Repository
Commit changes to the server:
Week 3-4: Frontend Development

Day 1-3: Basic Frontend Setup
Create Components for Trivia Game
Create components directory in client/src.
Create basic components: Question.js, Score.js, Leaderboard.js.
Style Components with CSS
Create styles directory in client/src.
Add basic styles to App.css and individual component CSS files.
Document Frontend Setup
Add Frontend_Setup.md to the docs directory with details on component structure and styling.
Day 4-6: API Integration in Frontend
Fetch Data from Backend
Display Data in Components
Modify components to display fetched data, e.g., showing images and choices.
Update GitHub Repository
Commit frontend changes:

Week 5-6: OpenAI API Integration and Game Mechanics
Day 1-3: Integrate OpenAI API
Obtain OpenAI API Key
Sign up for an API key from OpenAI.
Set Up OpenAI Integration
Create a route in server/index.js for OpenAI API:
Fetch OpenAI Data in Frontend
Example for fetching trivia questions from OpenAI API:
Document OpenAI Integration
Add OpenAI_Integration.md to docs with details on API usage and example responses.
Day 4-6: Implement Game Mechanics
Score Tracking
Implement score tracking in Score.js:
Leaderboard System
Create a simple leaderboard in Leaderboard.js:
Document Game Mechanics
Add Game_Mechanics.md to docs with details on score tracking and leaderboard implementation.
Week 7-8: Testing, Deployment, and Documentation
Day 1-3: Testing
Write Unit Tests
Use Jest for unit testing components and API routes.
Example test for Question.js:
