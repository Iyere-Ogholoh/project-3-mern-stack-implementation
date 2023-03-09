#project 3. MERN stack implementation.

##To deploy a simple To-Do application that creates To-Do lists

###Step 1 - Backend configuration and installing node.js

`sudo apt update`

![updating packages](./images/backend-configuration/updating-ubuntu.png)

`sudo apt upgrade`

![upgrading ubuntu](./images/backend-configuration/upgrading-ubuntu-step-1.png)

![upgrading ubuntu](./images/backend-configuration/upgrading-ubuntu-step-2.png)

![upgrading ubuntu](./images/backend-configuration/upgrading-ubuntu-step-3.png)

Get location of Node.js software from Ubuntu repositories

`curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -`

Install Node.js

`sudo apt-get install -y nodejs`

The command above installs both nodejs and npm. NPM is a package manager for Node like apt for Ubuntu, it is used to install Node modules & packages and to manage dependency conflicts.

![installing node.js](./images/backend-configuration/installin-node.js-step1.png)

![installing node.js](./images/backend-configuration/installin-node.js-step2.png)

![installing node.js](./images/backend-configuration/installin-node.js-step3.png)

verify node installation

`node -v`

![verifying node installation](./images/backend-configuration/vefifying-node-installation-1.png)

verify node installation

`npm -v`

![verifying node installation](./images/backend-configuration/veryfying-node-installation-2.png)

create a new directory for Todo project

`mkdir Todo`

`ls`

[verifying Todo directory was created](./images/backend-configuration/verifying-Todo-directory-created.png)

`ls -lih`

[showing information about files and directory](./images/backend-configuration/showing-info-about-files-and-directories.png)

change directory to newly craeted one

`cd Todo`

![changing directory to Todo directory](./images/backend-configuration/changing-directory-to-Todo-directory.png)

initialize project

`npm init`

![initializing project](./images/backend-configuration/initializing-project.png)

confirm package.json file was created

`ls`

![confirming creation of package.json file](./images/backend-configuration/confirming-creation-of-package.json-file.png)

update npm

`sudo npm install -g npm@9.6.1`

![updating npm](./images/backend-configuration/updating-npm.png)

###INSTALL EXPRESSJS





