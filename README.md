# LAMP-Stack-Application

STEP-BY-STEP GUIDE TO DEPLOY A LAMP STACK APPLICATION ON AMAZON LIGHTSAIL

1. Open Amazon Lightsail on the AWS Console

- Log in to your AWS Management Console.
- In the services menu, locate and click on Lightsail.

2. Create an Instance
- Click the Create instance button.

3. Select Your Instance Location
- Under Choose your instance location, select Virginia (us-east-1).
- Select an availability zone, Zone A (us-east-1a).

4. Select Your Instance Image
- In the Choose your instance image section, select Linux/Unix as the platform.

5. Select a Blueprint
- From the available blueprints, select LAMP (PHP 8).
  A blueprint is a pre-configured stack of software that allows you to deploy applications quickly. The LAMP (PHP 8) blueprint includes Linux, Apache, MySQL, and PHP.

6. Add a Launch Script

- You can optionally add a launch script. This script runs during the initial boot of the instance and   can be used to automate setup tasks such as updating packages, installing additional software, or configuring services.
- Click on the Add launch script link and enter your script. (Script is attached)


7. Choose an Instance Plan
- Select an instance plan based on your expected traffic and resource requirements. Amazon Lightsail offers several predefined plans with varying levels of CPU, RAM, and storage.
For a basic LAMP stack application, the cheapest plan might be sufficient to start with, and you can scale up as needed.

8. Enter a Name for the Instance
- Provide a unique name for your instance. For example, MyLAMPInstance.
- Click the Create instance button.


9. Configure Static IP
- Once the instance is created, navigate to the Networking tab in the Lightsail console.
- Click on Create static IP.
- Select the instance you just created from the dropdown menu.
- Click the Create button to assign the static IP to your instance. This ensures that the IP address of  your instance remains the same even if the instance is restarted.