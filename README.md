# jenkins-cloudformation
- Assign an EC2 Role with your Jenkins Instance with Admin (Resource Level Permissions) to Provision infrastructure
- Demo Slack Sharable Link: https://join.slack.com/t/newworkspace-syo3324/shared_invite/zt-1gggmw6ef-5fVzMLPRKyLuVf9wZ6mRKg

# Setup
- Create your channel (Private)
- Select your Channel
- Click on the Channel Name Drop Down at the top 
- Click on `Integrations` > Add an App
- 

- Go to Jenkins
    - Manage Jenkins
    - Manage Plugins
    - Click Available
    - Search `Slack Notification`
    - Select and Install Without Restart

- Go back to the Dashboard (We need to Pass our Slack Configuration)
    - Click again on Manage Jenkins
    - Configure system
    - Search for `Slack` (should be at the buttom)
        - Workspace: `jjtech-eagles-devops`
        - Credential: 
            - Step 3: Integration Token Credential 
        - Default channel / member id: `#jenkins-cloudformation-cicd`
        - CLICK ON `TEST CONNECTION`
        - NAVIGATE TO YOUR SLACK CHANEL TO CONFIRM THE JENKINS INTEGRATION NOTIFICATION




- Jenkins and Slack Integration Runbook: https://jjtech-eagles-devops.slack.com/services/B04425RQH5F?added=1