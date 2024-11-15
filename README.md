# jenkins-freestyle-project
This is a continuation of the jenkins-mini-project. Here, we are creating a freestyle project in jenkins



# Jenkins Job 
A job in jenkins is a unit of work or a task that can be executed by the jenkins automation server 



# Creating a freestyle Project

#### On the dashboard, select new item
![image](https://github.com/user-attachments/assets/9352b051-8e9a-4e65-bffa-2b8992e946ee)



#### Create a freestyle project named "my-first-job"
![image](https://github.com/user-attachments/assets/5e1e1d32-0af3-459c-a3aa-633641140b12)



# Connecting Jenkins to Source Code Management 

i. Create a new github repository called jenkins-scm with a README.md file 
ii. Connect jenkins to "jenkins-scm" repository by copying the repository code under HTTPS and pasting it in the jenkins freestyle repository url after selecting Git

![image](https://github.com/user-attachments/assets/bdadfca1-c064-4f43-8a81-1d75a3b7d092)

![image](https://github.com/user-attachments/assets/b3bad920-37ac-4897-b517-08e450274bf1)


# Save configuration and run "build now" to connect jenkins to the repository 
![image](https://github.com/user-attachments/assets/e42236cb-6f5a-463f-a505-84d0076047c1)


![image](https://github.com/user-attachments/assets/c35b1b6a-2908-453e-8a68-49f3e0238dd1)


# Jenkins has been successfully connected to github repository 

# Configuring Build Trigger 

![image](https://github.com/user-attachments/assets/f1ae673d-20c2-4e20-8b0c-a02ce87f9427)


#### Configure the webhook on Github
![image](https://github.com/user-attachments/assets/d2aba2eb-51db-4d79-8878-7947f8f31731)



#### Any changes to the github repositories will trigger automated build on the jenkins server. 




















































