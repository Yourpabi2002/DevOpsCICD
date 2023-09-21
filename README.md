
# DevOpsCICD

![Alt text](https://miro.medium.com/v2/resize:fit:1400/1*domBOWMvoJjeLUJkOHIyEg.png)

## Step-1

## Installation

Install the tools in your local machine-

- Git
- Java
- Jenkins (war file)
- Tomcat Server
- Apache Ant or Maven

Now you need to configure them 

![Screenshot 2023-09-21 013158](https://github.com/Yourpabi2002/DevOpsCICD/assets/100905194/880e7046-6a05-47f0-add3-020b5089ae63)

- add user var of Java
- JENKINS_HOME sys var with JENKINSHOME dir path
- ANT_HOME user var and add bin file to the Path var



    

## Step-2

move the jenkins.war file to the Tomcat webapp dir

![Screenshot (7)](https://github.com/Yourpabi2002/DevOpsCICD/assets/100905194/23047065-683c-4084-95fc-491624050c49)


Run jenkins from the Tomcat server using port localhost:8080/jenkins


![Screenshot (8)](https://github.com/Yourpabi2002/DevOpsCICD/assets/100905194/3132b0f2-0640-4830-a5ba-3e6581b3c265)


## Step-3

Now we are going to create all the jobs one by one 

Here is the ultimate architecture:

![WhatsApp Image 2023-09-21 at 2 18 25 AM](https://github.com/Yourpabi2002/DevOpsCICD/assets/100905194/6bb4577f-b050-4add-a890-b5adc8ad433e)

We need to install the plugins first
Go to Manage jenkins, then plugins and available plugins
Search and install

- github
- ant
- warning next generation
- JUnit
- Deploy to container
- Build Pipeline

  ![Screenshot (9)](https://github.com/Yourpabi2002/DevOpsCICD/assets/100905194/0f061fa0-6bab-4c31-9536-427cc35e78e4)


![Screenshot (10)](https://github.com/Yourpabi2002/DevOpsCICD/assets/100905194/7c18480a-03b3-4f38-a75f-f34e5de800e8)

Now Create jobs one by one

## Step-4
### All jobs step by step
for every job we will choose the freestyle project and modify them accordingly

![WhatsApp Image 2023-09-21 at 4 01 00 AM](https://github.com/Yourpabi2002/DevOpsCICD/assets/100905194/18e166c2-0a61-431e-8c1b-9e75e77191fc)


## Step-5
### CICD pipeline

-Now create a pipeline view and configure the job's post build action part to start another job build.
-githubpull is the initial job for the pipeline 

![](https://media.licdn.com/dms/image/C5622AQGVZAsB7uTW7Q/feedshare-shrink_2048_1536/0/1647025391147?e=1698278400&v=beta&t=pL8MgeErxwJvPucVBll2dWTtVkOJRvKwG0RnsbHJVvo)

![](https://miro.medium.com/v2/resize:fit:1200/0*YG-yFK5U3CVYFc7s.png)




