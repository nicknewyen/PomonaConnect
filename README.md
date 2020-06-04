HOW TO RUN APPLICATION

Step 1: run npm install in both root folder and client folder
Step 2: Create a default.json file in the config folder. 
Step 3: Inside the default.json file, include the following:

{
    "mongoURI": "insert-mongo-uri-here",
    "jwtSecret": "your-secret-token",
    "githubClientId": "your-github-client-id",
    "githubSecret" : "your-github-secret"
}

Step 4: run "npm run dev" in the root folder
