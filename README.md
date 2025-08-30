# My CICD App

This is a simple Hello World web application deployed using **AWS CodeCommit, CodeBuild, CodeDeploy, and CodePipeline**.

## Project Structure
```
my-cicd-app/
├── index.html        # Webpage to deploy
├── appspec.yml       # CodeDeploy instructions
├── buildspec.yml     # CodeBuild instructions
```

## Deployment Flow
1. Push code to CodeCommit (acts like GitHub).
2. CodePipeline triggers automatically.
3. CodeBuild packages files.
4. CodeDeploy deploys files to EC2 instance.
5. Access the web app in browser via EC2 Public IP.

## How to Submit
- Push this project to **CodeCommit** and then to **GitHub**.
- Add your **screenshots** (CodeCommit repo, CodeBuild, CodeDeploy, CodePipeline, Browser output).
- Share your GitHub repo URL in the portal.

## Terms & Conditions
- Do not share the confidential task document with anyone.
- Do not mention company name anywhere in the code or repo.
- The code is open-sourced only for learning/profile purposes.
