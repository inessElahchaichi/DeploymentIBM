![last2](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/c26fd092-78aa-486a-a971-11ffde96d0df)<!DOCTYPE html>
<html>
<body>
    <div class="container">
        <h1 class="title">Deploy a Model with IBM Watson Machine Learning</h1>
        <div class="section">
            <div class="section-title">Requirements</div>
            <div class="section-content">
                <p>An IBM Cloud Account.</p>
                
![1LOGIN](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/abeb4de5-45da-425c-998d-e241cb936efa)
            </div>
        </div>
        <div class="section">
            <div class="section-title">Create an IBM Cloud API Key</div>
            <div class="section-content">
                <p>To utilize the Watson Machine Learning service programmatically, an API key is required. Visit https://cloud.ibm.com/iam/apikeys, create a new API key, and remember to save and download it for future use.
                </p>
            </div>
        </div>
        <div class="section">
            <div class="section-title">Initiating a Project and the Initial Deployment Step</div>
            <div class="section-content">
                <p>Access IBM's Cloud Pak for Data service (Watson Studio) and go to the dashboard. Create a new project by selecting "Create a project" and choose an Empty project template. In the assets section, add a new asset by selecting the "Local"
                    option. Upload your IPYNB file and TXT files, then create the asset. Open your IPYNB file and follow the provided steps. Return to the Watson home page, go to the deployment section (same steps as creating the project), locate your
                    model, and click on "Deploy" or the rocket ship icon. A green tick indicates a successful deployment.</p>
                <img src="web_app_screenshot.png" alt="Web App Screenshot" width="400">
            </div>
        </div>
        <div class="section">
            <div class="section-title">Final Step</div>
            <div class="section-content">
                <p>Deploy the application on IBM Cloud through this [link](#). This option sets up a deployment pipeline, including a hosted Git lab project and a DevOps toolchain. After updating, the application will restart, and you can access it by clicking on the "Visit App URL" option.</p>
                <img src="web_app_screenshot.png" alt="Web App Screenshot" width="400">
            </div>
        </div>
    </div>
</body>
</html>
