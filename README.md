# AWS Amplify Hosting Practical

This simple HTML website is designed for deployment via GitHub -> AWS Amplify Hosting.

## Deploy
1. Create a GitHub repository.
2. Upload `index.html` and `amplify.yml` (at the repo root).
3. Open AWS Amplify Hosting -> Create new app -> GitHub.
4. Authorize GitHub access and choose the repository and `main` branch.
5. The repository's `amplify.yml` handles the build. Check its settings if prompted.
6. Choose Next -> Save and deploy.
7. When deployment succeeds, open the HTTPS URL shown by Amplify.

This is a website-hosting practical, not a virtual machine (EC2) practical.
#
