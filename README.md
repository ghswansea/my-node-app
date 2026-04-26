# my-node-app
ci cd demo using nodejs

For your Node.js + Docker app, here is a simple CI pipeline using GitHub Actions.

When you push code to GitHub, it will:
    Install dependencies
    Run tests
    Build Docker image
    Confirm build success
    
Project Structure
        mynode/
        ├── app.js
        ├── package.json
        ├── Dockerfile
        └── .github/
            └── workflows/
                └── ci.yml
