# Building-and-Deploying-a-Mobile-Application-with-Azure-SDK
In this project, I took on the complete lifecycle of building and deploying a mobile application using Azure SDK by Microsoft. The project encompassed two fundamental phases:

![image](https://github.com/Mourad-Amraouy/Building-and-Deploying-a-Mobile-Application-with-Azure-SDK/assets/146946535/e71bb7dc-9768-4880-8441-20774cae12e4)


The development of mobile applications has become a major issue for many companies and developers. With the rapid evolution of technologies and the growing demand from users for high-performance and secure mobile applications, it is essential to have a reliable platform to deploy and run these applications. Azure, Microsoft's cloud computing platform, offers a range of services for mobile application developers, making it easy to deploy, run and manage applications on the cloud. In this report, we will explore how to run a mobile application (for example, Calculator) in Azure using the Eclipse development environment.
Azure, développé par Microsoft, est l'une des plateformes de cloud computing les plus populaires et largement utilisées dans le monde. Elle offre une gamme complète de services et de solutions pour le déploiement, la gestion et la mise à l'échelle d'applications, de services et de ressources informatiques dans le cloud. Azure propose une vaste gamme de services, notamment l'hébergement d'applications web, la gestion de bases de données, l'analyse de données, l'intelligence artificielle, l'Internet des objets, la sécurité et bien d'autres encore. Elle offre également une grande flexibilité avec des options de déploiement hybride, permettant d'intégrer facilement des applications locales avec le cloud. Azure bénéficie d'une large présence mondiale avec de nombreux centres de données répartis dans le monde entier, offrant une performance élevée et une disponibilité élevée. Elle est largement utilisée par les entreprises de toutes tailles, les développeurs et les professionnels de l'informatique pour créer et déployer des applications modernes et évolutives dans le cloud.

![image](https://github.com/Mourad-Amraouy/Building-and-Deploying-a-Mobile-Application-with-Azure-SDK/assets/146946535/ed2da978-5b8b-4f3a-aae8-8201a56b2ce3)

### 1.Azure Microsoft account creation
   Access the Azure website: Go to the Azure website at https://azure.com in your web browser.
   
![image](https://github.com/Mourad-Amraouy/Building-and-Deploying-a-Mobile-Application-with-Azure-SDK/assets/146946535/60ea01c0-0f6d-4483-bae6-662c80bcf4b9)

 To sign in with a Microsoft account or create a new account: If you already have a Microsoft account (for example, a Outlook.com or an Xbox Live account), you can log in using this information. Alternatively, you can create a new account by clicking on "Create an Account" and following the instructions to provide the necessary information, such as your name, email address and a password.
 How to Fill in billing information: To create a free Azure account, you will need to provide billing information, although you will not be charged for free use. This may include information such as your name, address, phone number and credit card details. You can also choose to use a PayPal account.
 How to Select a free subscription: Azure offers various subscription levels, including a free subscription that allows you to use certain services for free for a limited period of time. Select the free subscription to get started.
 To Verify your identity: For security reasons, you may be required to verify your identity by providing a valid phone number or credit card. Follow the instructions to perform the verification. 
 To Accept the terms of use: Read and accept the Azure Terms of use to finalize the creation of your account.
 Configuration du compte : Une fois que vous avez créé votre compte Azure, vous pouvez configurer vos paramètres, tels que la langue, la région et les préférences de communication.
3.	L’installation de azure SDK dans l’environnement Eclipse 
L'installation d'Azure sur l'environnement Eclipse implique plusieurs  étapes. Voici un guide général pour vous aider dans ce processus :
Étape 1 : Installation d'Eclipse
Assurez-vous que vous avez Eclipse installé sur votre système. Si ce n'est pas le cas, vous pouvez le télécharger à partir du site officiel d'Eclipse (https://www.eclipse.org/).
 Step 2 Configuring the Java Development Kit (JDK)
Azure requires Java Development Kit (JDK) to work properly. Make sure you have JDK installed on your system and configure it in Eclipse. You can download JDK from the official Oracle website (https://www.oracle.com/java/technologies/javase-jdk14-downloads.html ) and follow the installation instructions.
Mount your ISO file on the medium of your choice (CD/DVD, USB key), insert it into your machine and boot on it.
If you don't know how to do this, go to this part of the course which explains how to boot on the Ubuntu installation CD. Here, we don't want to install Ubuntu, but the BIOS configuration to be done is the same.
Step 3 Installing the Azure plugin for Eclipse
The Azure plugin for Eclipse is a tool that allows you to develop and deploy Azure applications directly from the Eclipse environment. Here's how to install it :
 Open Eclipse and go to the "Help" menu > "Eclipse Marketplace" (Eclipse Marketplace).
 Step 4: Configuring Azure Credentials
Once you have installed the Azure plugin for Eclipse, you must configure the Azure credentials to be able to access your Azure resources. Here's how to do it :

In Eclipse, go to the Azure perspective by selecting "Window" > "Perspective" > "Open Perspective" > "Azure" from the menu bar.
Click on the "Sign in to Azure" icon in the "Azure Explorer" view.
Follow the instructions to log in to your Azure account by providing your Azure credentials.    
Step 5: Using the Azure plugin for Eclipse
Now that you have installed and configured the Azure plugin for Eclipse, you can use it to develop and deploy Azure applications. You can create and manage Azure resources, deploy web applications, Azure functions, Docker containers, and much more, directly from the Eclipse environment.


The development of mobile applications has become increasingly popular with the proliferation of smartphones and tablets. A mobile calculator is a common example of a simple and useful application that you can create to familiarize yourself with mobile application development using Java and Eclipse.

### 2. Development

Step 1: Creating a new project

In Eclipse, create a new project by selecting "File" > "New" > "Project" from the menu bar.
Choose "Java Project" as the project type, then click "Next".
You give your project a name and choose the destination directory, then click on "Finish" to create the project.

Step 2: Application Development 

Define the basic features of your calculator, such as the number buttons, the operations buttons, and the display of the results.
You implement the calculation logic in your application using Java. You can define event listeners for buttons, manage user input, and perform the necessary calculations.
Use the built-in development tools in Eclipse, such as the code editor, debugger and graphic design tools, to facilitate the development process.


Step 3: Testing the application

Use an emulator or a mobile device to test your application. You can set up an Android emulator in Eclipse to test your application on different Android devices, or connect a real mobile device to test the application live.
You perform extensive tests to ensure that your application is working correctly, dealing with different usage scenarios and checking the calculation results.

### 3. The deployment

Direct deployment from Eclipse :
You can use Azure plugins for Eclipse to deploy your application directly from Eclipse to the created App Service resource.

<img width="496" alt="1" src="https://github.com/Mourad-Amraouy/Building-and-Deploying-a-Mobile-Application-with-Azure-SDK/assets/146946535/ff2f7086-40e5-46c5-97ea-9f6779bd9439">

After creating our app

<img width="389" alt="2" src="https://github.com/Mourad-Amraouy/Building-and-Deploying-a-Mobile-Application-with-Azure-SDK/assets/146946535/88fe46ee-d102-41cc-9c46-1e7899223b2c">

End of deployment in azure

<img width="530" alt="HGHCHCFH" src="https://github.com/Mourad-Amraouy/Building-and-Deploying-a-Mobile-Application-with-Azure-SDK/assets/146946535/d9d3fa39-d09e-4254-a78c-457c862b69be">


 Verification and testing of the application :
Once the application is deployed, you can access the application URL on App Service to check and test it.
Perform extensive tests to ensure that your application works correctly on App Service, processing different usage scenarios and checking the calculation results.

<img width="512" alt="4" src="https://github.com/Mourad-Amraouy/Building-and-Deploying-a-Mobile-Application-with-Azure-SDK/assets/146946535/27d99fa6-7fe0-42fe-8504-3458aab6a376">



