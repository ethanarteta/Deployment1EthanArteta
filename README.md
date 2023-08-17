<p align="center">
<img src="https://github.com/kura-labs-org/kuralabs_deployment_1/blob/main/Kuralogo.png">
</p>
<h1 align="center">C4_deployment-1<h1> 

Demonstrate your ability to run a Jenkins build and manually deploy to Elastic Beanstalk.

- Create a separate GitHub repository for this application 

- Download the files from this repository and upload them to your newly created repository 

- Be sure to follow the deployment instructions from this Repository  

- Document your progress in a .md file in your repository. Also, document any issues you may run into and what you did to fix them.

- Lastly, save your documentation and diagram into your repository. Submit your repository link to the LMS

## Deployment instructions Link:
-  Link to instructions: https://github.com/kura-labs-org/c4_deployment-1/blob/main/Deployment-instructions.md






# Deployment Documentation

This document outlines the steps taken to deploy the application.

### Steps Taken:

1. **Download and Extract Files:**  
   - Downloaded GitHub files from KuraLabs.
   - Unzipped the files and copied them.

2. **Repository Setup:**  
   - Created a new repository.
   - Pasted the downloaded files into the repository.

3. **Jenkins Configuration:**  
   - Logged in to Jenkins, created by Tyrone.
   - Created a new build named "Deployment1EthanArteta".

4. **GitHub Token Generation:**  
   Generated a new token from GitHub for authentication.

5. **Jenkins Credentials:**  
   Created new credentials in Jenkins for deploying GitHub files.

6. **Pipeline Setup:**  
   - Applied and saved the pipeline build configuration.

7. **Application Build:**  
   Successfully ran the application in Jenkins with no errors.

8. **Manual Deployment to Elastic Beanstalk:**  
   - Downloaded zip folders for manual deployment to Elastic Beanstalk.

9. **Scribe Documentation:**  
   Followed the deployment steps outlined in the Scribe Documentation.

10. **Initial Deployment Issue:**  
    Encountered a 502 error code during the first deployment.

11. **Troubleshooting:**  
    - Analyzed logs and identified the issue as an incorrectly zipped app file.
    
12. **File Correction:**  
    - Re-zipped the application file correctly, excluding the parent folder.

13. **Redeployment:**  
    Followed Scribe instructions again to redeploy the app.

14. **Successful Deployment:**  
    Successfully deployed the application onto Elastic Beanstalk.

### Images:

![Elastic Beanstalk Confirmation](https://github.com/ethanarteta/Deployment1EthanArteta/blob/6ae6d46550b523a4c40ee28e317731a1d6351c99/Elastic%20Beanstalk%20Confirmation.png)

![Deployment Step 1](https://github.com/ethanarteta/Deployment1EthanArteta/blob/7293a65e50d3255ba413608ab76672e8d18df7dc/Deployment%201.png)
