# CAPM-Student-Notes
Notes for Udemy Course-**SAPUI5/Fiori FullStack on BTP | RAP/ABAP Cloud&amp; SAP BTP CAPM**


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


After downloading and unzipping the folder, all the required files will be copied automatically.


Next, install Docker Desktop on your machine.

Finally, open VS Code and install the Dev Containers extension to enable container-based development.




