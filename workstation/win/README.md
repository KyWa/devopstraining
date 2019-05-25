# Setup for DevOps on a Windows Workstation

## Scope

The scope of setup here is getting Windows to a state to use modern tooling. This may change when WSL2 comes along with the new Windows Terminal as there are notes about more features being added.

## Setup

WSL should be the first thing to setup as you will have to reboot. After that, the rest of the tooling can be installed and used without a reboot.

## Applications

1. WSL
2. VS Code
3. Terraform

### WSL

* Please note WSL is only needed if you are going to be using Ansible. If you plan on doin your work without Ansible (ie. Terraform, Git) you do not need the WSL.

First step is to go to the Start menu and type in "Turn Windows features on or off". From this menu go towards the bottom and look for Windows Subsystem for Linux and check the box. Click OK and Windows will begin to download and install the roles and will ask to reboot once it has completed. Go ahead and click Reboot Now. Once your system is back from its reboot, go to the Microsoft Store application. From the Microsoft Store search for Linux. There will be a few options show up, but we are going to use Ubuntu as its the most common and is what the majority of people will be using. If you have a prefernce for another one, please choose what you are comfortable with. Click on Ubuntu (there may be multiple versions) and click install. It may take a moment to install. Once its complete (you will see a notification) click Start and type Ubuntu. 

A terminal will load up and ask for a username. Create a user by typing in the username. After you have typed in your username and pressed Enter it will prompt you to create a password. Please note this password is only for your user on the WSL and has no ties to your Windows password. Once this is done it will continue its setup. Load the terminal again by typing Ubutnu in the Windows Search bar and pressing return. You should now be in your Ubuntu terminal and can install Ansible by running: `sudo apt install ansible -y`.

### VS Code

### Terraform
