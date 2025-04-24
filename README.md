# CAPM-Student-Notes
Notes for Udemy Course-**SAPUI5/Fiori FullStack on BTP | RAP/ABAP Cloud&amp; SAP BTP CAPM**

Link to the course :-

https://www.udemy.com/course/professional-sapui5-web-application-development-part-1/?srsltid=AfmBOooeUxObJ6BOogsYye3aUwhgVGcsE_qeNrG5NHPKilETG3Z98y9u&couponCode=ST8MT220425G3


Different Ways to Develop CAPM Applications:

	1. SAP Business Application Studio (BAS)
A cloud-based IDE provided by SAP specifically tailored for CAPM development.

	2. Visual Studio Code with Local Software Setup on our Local Machine!

Install all required CAPM tools and SDKs directly on your local machine.

	3. Visual Studio Code with Docker Container – install all needed software on the Docker container instead of our Local Machine!

Use Docker Desktop to run a container image with all necessary tools installed—keeping your local machine clean.

	4. GitHub Codespaces
A cloud-based development environment hosted by GitHub, pre-configured with necessary tools.

	5. Other Editors
Various other editors can also be used, such as Jenkins IDE, depending on your workflow.




An advantage of a Docker container image is that it allows us to install specific software with specific versions, tailored to the needs of a particular project. This software gets installed inside the container image, which we can run on our local machine. At the same time, our system remains free of any development tools, keeping it clean and conflict-free.

For example, if one project needs Node.js version 19, we can create a container with Node.js 19 installed.
If another project needs Node.js version 20, we can create a separate container image with Node.js 20.
This way, each project gets the exact version it needs, and we don’t have to install or switch versions on our local machine.

In simple words, using a dev container is a great way to:

	• Start coding quickly with all the required tools already set up inside the container – without installing anything on our local machine
 
	• Skip the headache of installing and configuring software-Since everything is defined in the container
          (e.g., via Dockerfile or devcontainer.json), you don’t need to manually install anything on your main system.
 
	• Work in a clean and focused space without affecting your main computer-The container 
 	is isolated from your host system, meaning no clutter or version conflicts on your local machine.
  
	• Try things out freely—even if you break something, you can reset easily-Containers can be recreated instantly. 
 	If something goes wrong, just rebuild the container and you're back to a clean slate.
  
	• Share the same setup with teammates so everyone works in the same environment-Sharing the devcontainer.json and 
 	related files ensures all team members get the same dev environment, reducing "it works on my machine" problems.

If we want to set up a development container, we should follow the official guidelines provided at https://containers.dev.

Below is the folder structure that we need to create on our Laptop/Desktop—this can be placed in any preferred location.

<img width="1468" alt="image" src="https://github.com/user-attachments/assets/ce07aa53-75bc-44af-9160-1ff92e8634ad" />

Download ZIP Folder from GITHUB!

<img width="1464" alt="image" src="https://github.com/user-attachments/assets/d3fd9189-3129-4b02-b03a-e126fd609646" />


After downloading and unzipping the folder, all the required files will be copied automatically.


Next, install Docker Desktop on your machine.

Open VS Code and install the Dev Containers extension to enable container-based development.

<img width="1461" alt="image" src="https://github.com/user-attachments/assets/1bfee879-3f23-4e9a-b668-2c36bfce08b3" />

Now open the folder in VS Code

<img width="1470" alt="image" src="https://github.com/user-attachments/assets/3bd23a79-5839-4a5d-9f1e-6e7acc6aad70" />

As soon as we open we open specified folder in which devcontainer.json is maintained VSCode will give a prompt to us whether 
we can open the container 

<img width="1470" alt="image" src="https://github.com/user-attachments/assets/fcf494c9-8bf2-45a8-901e-656ba86357db" />


Now we are connected to container environment from VSCode . Container contains all the software installed in it and we dont have to 
install needed software to RUN CAP Applications.


