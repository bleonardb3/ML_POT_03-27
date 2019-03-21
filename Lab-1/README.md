# Lab-1 Setup Environment
 
## Introduction:

This lab will set up the environment that will be used by the subsequent labs. 

## Objectives:

Upon completing the lab, you will know how to:

1. Create a new project. 
1. Create an object storage instance and associate it with the project. 
1. Create a machine learning instance and associate it with the project. 
1. Create a Spark instance and associate it with the project. 

## Instructions:

### Step 1.  Log into your Watson Studio account at datascience.ibm.com, then click on the hamburger icon, then `Projects`, and then `View All Projects`
> <img src="https://github.com/bleonardb3/DS_POT_02-07/blob/master/images/Navigation%20Selection.png"/>
> <img src="https://github.com/bleonardb3/DS_POT_02-07/blob/master/images/ViewAllProjects.png"/>


### Step 2.  Click on `New Project`. 
> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Select%20New%20Project.png"/>

### Step 3. Hover the mouse over `Standard` 
> <img src="https://github.com/bleonardb3/ML_POT_03-27/blob/master/Lab-1/images/HoverMouseOverStandard.png"/>

### Step 4. Click on `Create Project`. 
> <img src="https://github.com/bleonardb3/ML_POT_03-27/blob/master/Lab-1/images/CreateStandardProject.png"/>

### Step 5. Enter the project name (eg. Watson Studio Labs), optionally a description, de-select the `Restrict who can be a collaborator  checkbox` and then click on `Add` in the Storage section. Note if you have already provisioned cloud object storage (you shouldn't see an Add button) , then just click on the `Create` button, and skip to Step 9. 

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/New%20Project%20Panel%20-%20Add%20Storage.png"/>

### Step 6. Click on the Lite plan, and then click on `Create`. 

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Create%20Object%20Storage.png"/>

### Step 7. Optionally change the storage name, and then click on `Confirm`

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Confirm%20Creation.png"/>

### Step 8. Click on `Refresh`. 

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Click%20Refresh.png"/>

### Step 9.  The cloud object storage should appear. Now click on `Create`. 

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Click%20Project%20Create.png"/>

### Step 10.  Click on the project `Settings` tab.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20Settings.png"/>

### Step 11. Scroll down to `Associated Services`, then select `Add service` and select `Watson`.

> <img src="https://github.com/bleonardb3/WatsonStudio/blob/master/images/SelectWatsonService.png"/>

### Step 12. Select the `Machine Learning` service 

> <img src="https://github.com/bleonardb3/WatsonStudio/blob/master/images/SelectMachineLearningService.png"/>

### Step 13. Select `New`.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20New%20Service.png"/>

### Step 14. Select the `Lite` plan. 

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20Lite%20ML.png"/>

### Step 15. Scroll down and click `Create`, then change the `Service name` to `Machine Learning` in the `Confirm Creation` panel and click `Confirm`.  

> <img src="https://github.com/bleonardb3/WatsonStudio/blob/master/images/ConfirmMachineLearningCreation.png"/>

### Step 16. The Machine Learning service that you created should now appear in `Associated Services`. 

> <img src="https://github.com/bleonardb3/ML_POT_03-27/blob/master/Lab-1/images/AssociateMLService.png"/>

### Step 17. Repeat steps 11-16 to create a Spark service. 

### Step 18. The Associated Services should appear as below. 

> <img src="https://github.com/bleonardb3/ML_POT_03-27/blob/master/Lab-1/images/DisplayAssociatedServices.png"/>


