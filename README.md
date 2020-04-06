# SageMaker Workshop

  **Description:** This workshop was created to walk users through the end-to-end process and considerations for utilizing SageMaker for Machine Learning. The workshop focuses on a usecase of predicting whether a transaction is likely to be a recurring payment (i.e. subscription, membership).  
  
 The workshop is broken into 3 Labs with an additional step for lab setup: 
 
   * Lab Setup
   * Lab 1: Data Exploration & Processing
   * Lab 2: Training
   * Lab 3: Hosting and Evaluating
    
 ---
 
 ## Lab Setup
    
   ### Create SageMaker Notebook Instance 
   
   1) Login to your AWS Account
   2) Go to [Amazon SageMaker Service](https://console.aws.amazon.com/sagemaker/)
   3) Ensure you are in *us-east-1/N.Virginia*
   4) Select **Notebook instances** from the left menu
   5) Select **Create notebook instance** in the upper right corner
   6) Under *Notebook Instance Settings*, complete/update the following:
       * **Notebook instance name:** Enter a name for the notebook instance (Ex: sagemaker-workshop-janedoe)
       * **Notebook instance type:** ml.t3.large
   7) Under *Permissions and encryption*, complete/update the following:
       * **IAM Role:** Create a new role --> Select 'any S3 bucket' --> Create Role
   8) Under *Git Repositories*:
       * select 'Clone a public git repository to this notebook instance only' from the dropdown
       * Enter 'https://github.com/seigenbrode/sagemaker-workshop/' under *Git Repository URL*
   8) Leave all other sections using default settings, then click **Create notebook instance**
   9) It will take a few moments for the **Status** to change to **InService**
   10) Once the notebook is showing **InService**, click the **Open Jupyter** link to open your hosted notebook instance
   
 ---
 
 ## Lab 1: Data Exploration & Processing  
   
 From within the notebook instance we create in Lab Setup above:
 
   1) Go to the **Files** tab
   2) Click **sagemaker-workshop**
   3) Click **Lab1-DataExploration-Processing.ipynb** to open Lab 1
   4) The remaining steps for this lab are performed within the notebook instance
   
---
 
 ## Lab 2: Training
   
 From within the notebook instance we create in Lab Setup above:
 
   1) Go to the **Files** tab
   2) Click **sagemaker-workshop**
   3) Click **Lab2-Training.ipynb** to open Lab 2
   4) The remaining steps for this lab are performed within the notebook instance
   
---
 
 ## Lab 3: Hosting & Evaluation
   
 From within the notebook instance we create in Lab Setup above:
 
   1) Go to the **Files** tab
   2) Click **sagemaker-workshop**
   3) Click **Lab3-Hosting-Evaluuation.ipynb** to open Lab 3
   4) The remaining steps for this lab are performed within the notebook instance
       
