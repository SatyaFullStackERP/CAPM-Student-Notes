# CAPM-Student-Notes
Notes for Udemy Course-SAPUI5/Fiori FullStack on BTP | RAP/ABAP Cloud&amp; SAP BTP CAPM


Different Ways to Develop CAPM Applications:

	1. SAP Business Application Studio (BAS)
A cloud-based IDE provided by SAP specifically tailored for CAPM development.

	2. Visual Studio Code with Local Setup
Install all required CAPM tools and SDKs directly on your local machine.

	3. Visual Studio Code with Docker Container
Use Docker Desktop to run a container image with all necessary tools installed—keeping your local machine clean.

	4. GitHub Codespaces
A cloud-based development environment hosted by GitHub, pre-configured with necessary tools.

	5. Other Editors
Various other editors can also be used, such as Jenkins IDE, depending on your workflow.




An advantage of a Docker container image is that it allows us to install specific software with specific versions tailored to the needs of a particular project.

For example, if one project requires Node.js version 19, we can use a container where Node.js 19 is installed.

For another project that needs Node.js version 20, we can create a separate container image with Node.js 20 installed, and use that for development.

So DEV Containers can be used to work with a set of predefined software and specific software versions, without installing all the required software on our machine.

Dev containers can run on our machine without cluttering it with all the software that would otherwise need to be installed locally.

In simple words, using a dev container is a great way to:

	• Start coding quickly with all the right tools already set up
 
	• Skip the headache of installing and configuring software-Since everything is defined in the container
          (e.g., via Dockerfile or devcontainer.json), you don’t need to manually install anything on your main system.
 
	• Work in a clean and focused space without affecting your main computer-The container 
 	is isolated from your host system, meaning no clutter or version conflicts on your local machine.
  
	• Try things out freely—even if you break something, you can reset easily-Containers can be recreated instantly. 
 	If something goes wrong, just rebuild the container and you're back to a clean slate.
  
	• Share the same setup with teammates so everyone works in the same environment-Sharing the devcontainer.json and 
 	related files ensures all team members get the same dev environment, reducing "it works on my machine" problems.

