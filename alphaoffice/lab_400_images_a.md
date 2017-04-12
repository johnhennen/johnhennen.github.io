
- Top image 

    ![](images/lab400a/400_00_01_Lab300TopImage.png)  



Update: January 28, 2017

# Introduction

This is the second of several labs that are part of the **Oracle Public Cloud DevOps Cloud Native Microservices workshop.** This workshop will walk you through the Software Development Lifecycle (SDLC) for a Cloud Native project that will create and use several Microservices.

In the first lab (100), the Project Manager created a new project in the Developer Cloud Service, added team members to the project, and created and assigned tasks to the developers of this application. In this lab, you will assume the persona of the Java developer, who will be tasked with creating several microservices that will supply data to any required front-end or analytics components (one of which you will build in the following lab, lab 300).

Please direct comments to: Dennis Foley (dennis.foley@oracle.com)

## Objectives

- Access Developer Cloud Service
- Import Code from external Git Repository
- Import Project into Eclipse
- Build and Deploy project using Developer Cloud Service and Oracle Application Container Cloud Service

## Required Artifacts

- The following lab requires an Oracle Public Cloud account that will be supplied by your instructor. You will need to download and install latest version of Eclipse

# Create Initial Static Twitter Feed Service

## Explore Developer Cloud Service

### **STEP 1**: Login to your Oracle Cloud account as Bala.Gupta

- DCS console before choosing Agile menu item

    ![](images/lab400a/400_01_01_project_console.png)  

- John Dunbar

    ![](images/lab400a/400_01_02_johndunbar.png) 

- Agile menu choice

    ![](images/lab400a/400_01_03_agilemenuchoice.png)  

- active sprints Swim lanes - all 4 sprints in to do

    ![](images/lab400a/400_01_04_activesprints0.png)

- Drag and drop create microsystems repositories to in progress -should have red arrow

    ![](images/lab400a/400_01_05_sprint31.png)

- Confirm change - click next

    ![](images/lab400a/400_01_06_sprint32.png)

- Confirm change - click ok

    ![](images/lab400a/400_01_07_sprint33.png)

- swim lane after change

    ![](images/lab400a/400_01_08_sprint34.png)

### **STEP 2**: 

- New Repository button

    ![](images/lab400a/400_02_01_repository1.png)

- New Repository entry popup - name box should have red border

    ![](images/lab400a/400_02_02_repository2.png)

- Repository showing code files

    ![](images/lab400a/400_02_03_repository3.png)

### **STEP 3**: 

- Build menu item - New Job button - Build menu item and new job button should be in red elipses

    ![](images/lab400a/400_03_01_build1.png)

- New Job popup with job name and create a free-style job radio button

    ![](images/lab400a/400_03_02_build2.png)

- build job configuration popup main tab

    ![](images/lab400a/400_03_03_build3.png)

- build job configuration popup source control tab

    ![](images/lab400a/400_03_04_build4.png)

- build job configuration popup triggers tab

    ![](images/lab400a/400_03_05_build5.png)

- build job configuration popup build steps tab and build-steps drop down

    ![](images/lab400a/400_03_06_build6.png)

- build job configuration popup build steps tab - npm install

    ![](images/lab400a/400_03_07_build7.png)

- build job configuration popup post build tab 

    ![](images/lab400a/400_03_08_build8.png)

- build job working or in queue 

    ![](images/lab400a/400_03_09_build9.png)

- build job built

    ![](images/lab400a/400_03_10_build10.png)

### **STEP 4**: 

- Pick Deploy in Menu and New Configuration button - both should have red circles

    ![](images/lab400a/400_04_01_deploy1.png)

- New configuration popup - drop down with red circle around application container cloud

    ![](images/lab400a/400_04_02_deploy2.png)

- Enter data center username password - test connection

    ![](images/lab400a/400_04_03_deploy3.png)

- Enter data center username password - use connection

    ![](images/lab400a/400_04_04_deploy4.png)

- configuration popup - make sure select Node instead of java

    ![](images/lab400a/400_04_05_deploy5.png)

- Will show deploy in process then deploy completed

    ![](images/lab400a/400_04_06_deploy6.png)

- If arrow is not green, but is orange and pointed down, then need to manually start

    ![](images/lab400a/400_04_07_deploy7.png)

- To manually start, stop or redeploy, go to the gear dropdown icon

    ![](images/lab400a/400_04_08_deploy8.png)

### **STEP 5**: 

- Drag and drop task 3 to verify code - need red arrow
- This should be delayed until repository is created for second microservice 

    ![](images/lab400a/400_05_01_sprint34.png)

  ***NOTE***:

- Click next

    ![](images/lab400a/400_05_02_sprint35.png)

  **NOTE**:

- Enter 1 days and click OK

    ![](images/lab400a/400_05_03_sprint36.png)

Just plain paragraph here

- Moved to Verify code

    ![](images/lab400a/400_05_04_sprint37.png)


