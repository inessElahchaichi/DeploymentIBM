<html>
<body>
    <div class="container">
        <h1 class="title">Deploy a Model with IBM Watson Machine Learning</h1>
        <div class="section">
            <div class="section-title">Requirements : </div>
            <div class="section-content">
                <p> An IBM Watson Machine Learning Instance : You need to have an active instance of IBM Watson Machine Learning service in your IBM Cloud account
                    Patience (طول البال): Remember, deploying a model and working with new technologies can sometimes be challenging. Patience is key! If you encounter difficulties, take a deep breath, review the steps, and remember that learning and troubleshooting are all part of the journey in technology.
                    Compatible Data and Model Files: Ensure you have the necessary data and model files, typically in formats that are compatible with IBM Watson Machine Learning (like .ipynb for Jupyter notebooks).
                    
                </p>
                
![1LOGIN](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/abeb4de5-45da-425c-998d-e241cb936efa)
            </div>
        </div>
        <div class="section">
            <div class="section-title">Create an IBM Cloud API Key</div>
            <div class="section-content">
                <p>To utilize the Watson Machine Learning service programmatically, an API key is required. Visit https://cloud.ibm.com/iam/apikeys, create a new API key, and remember to save and download it for future use.
                ![2](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/9dcd7884-1ad8-49d1-b8a8-bf5f136a0679)
                ![3](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/15ea3fc8-c385-486b-a1ed-049b5a64afea)
                ![4](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/7225353b-de83-44f2-a615-cc3e5b9f3ce1)
                </p>
            </div>
        </div>
        <div class="section">
            <div class="section-title">Initiating a Project and the Initial Deployment Step</div>
            <div class="section-content">
                <p>Access IBM's Cloud Pak for Data service (Watson Studio) and go to the dashboard. Create a new project by selecting "Create a project" and choose an Empty project template. In the assets section, add a new asset by selecting the "Local"
                    option. Upload your IPYNB file and TXT files, then create the asset. Open your IPYNB file and follow the provided steps. Return to the Watson home page, go to the deployment section (same steps as creating the project), locate your
                    model, and click on "Deploy" or the rocket ship icon. A green tick indicates a successful deployment.</p>

![6](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/ff57120d-4de9-4924-b262-f4e57ad4be95)
![7](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/3e4f0868-6c6b-4753-978c-d4baf4b5c4a9)
![8](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/4ea2f854-2795-417d-a94b-400e3d2c558a)
![9](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/4942791e-e5d1-428e-9f0e-6af6a424b945)
![10](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/dbeac583-e7e5-4ec7-afc6-516ccf81f558)
![CODE](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/f364ab3d-954e-4328-a845-f04885ea7bad)
![code2](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/490c3afc-2da6-41e2-9ee0-a29c73189df0)
![code3](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/fe3d67a2-84ee-4825-8f2c-3a70526b829b)
![code4](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/73f0216e-e7fa-476e-9deb-dece3cdca19a)
![code5](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/e5463059-96cf-4a4b-a1d1-0a1e70b4fca6)
![code6](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/5878a46f-b755-4102-a6d1-41e347ad9b16)
![end1](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/a02a8171-9e99-4022-901d-043c192868c3)
![last1](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/8fdfe75f-715c-48d0-9e6e-dd5e55f13028)
![last2](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/95d52eab-59ed-4aff-a8fe-952ba8e6632b)
            </div>
        </div>
        <div class="section">
            <div class="section-title">Final Step</div>
            <div class="section-content">
                <p>Deploy the application on IBM Cloud through this https://cloud.ibm.com/devops/getting-started?env_id=ibm:yp:eu-de . This option sets up a deployment pipeline, including a hosted Gitlab project and a DevOps toolchain. After updating, the application will restart, and you can access it by clicking on the "Visit App URL" option.</p>

![last3](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/b990ed27-144f-4253-9abd-76dd93393976)
![last4](https://github.com/inessElahchaichi/DeploymentIBM/assets/115805947/7aeb8e30-b500-47f3-bec2-7f5598329a7b)
            </div>
        </div>
    </div>
<div class="section">
    <div class="section-title">Troubleshooting the Final Step </div>
    <div class="section-content">
        <p>If you encountered issues with the final step, don't worry; here's an alternative solution. During the deployment process, you will come across a Python code snippet. Copy this code snippet.</p>
        <p>Remember the API key we downloaded earlier? You'll need to incorporate the information from that downloaded file into the Python code. Import the JSON library and modify the code according to your requirements.</p>
        <p>If you are comfortable with programming languages other than Python, explore the code fragments provided. You may find alternative solutions in languages other than Python to resolve any issues.</p>
    </div>
</div> 
