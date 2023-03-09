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

`npm install express`

![installing expressjs](./images/installing-express-js/installing-expressjs.png)

create file index.js

`touch index.js`

![creating file index.js](./images/installing-express-js/creating-file-index.js.png)

`ls`

![confirming index.js file was created](./images/installing-express-js/confirming-index.js-created.png)

install the dotenv module

`npm install dotenv`

![installing dotenv module](./images/installing-express-js/installing.dotenv-module.png)

open index.js file

`vim index.js`

![pasting code in vim](./images/installing-express-js/pasting-code-in-vim.png)

 start our server to see if it works. Open your terminal in the same directory as your index.js file and type: node index.js

 `node index.js`

![starting server to see if it works](./images/installing-express-js/starting-server-to-see-it-it-works.png)

edit inbound rules in AWS console

![editing security groups inbound rules](./images/installing-express-js/editing-inbound-security-group-rules.png)

[opening url with public IP in browser](http://3.70.240.168:5000/)

![opening url with public IP](./images/installing-express-js/opening-url-public-ip.png)

create routes that will define various endpoints that the To-do app will depend on

`mkdir routes`

change dirctory to routes directory

`cd routes`

create a file api.js

`touch api.js`

open the file api.js with vim

`vim api.js`

paste code with vim

![pasting code with vim](./images/installing-express-js/pasting-code-in-vim-2.png)





