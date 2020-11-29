# Virtual Machine Documentation
This text explains how to interact with the vagrant virtual machine attached in this repository. 

## Pre-requisites 
1. Ruby
2. IDE 
3. Vagrant 
4. Virtual Box

### 1. Ruby
You need Ruby because it is the language in which the `Vagrantfile` which configures the virtual machine is written in. Ensure to download x64 for your OS

- For windows click [here](https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-2.6.6-1/rubyinstaller-devkit-2.6.6-1-x64.exe)
- For Mac click [here](https://www.ruby-lang.org/en/downloads/)

### 2. IDE
__Optional:__ It is easier to interact with the machine's vagrantfile when using a code editor, such as Visual Studio Code.
- You can learn how to [install VSC here](https://docs.microsoft.com/en-us/visualstudio/install/install-visual-studio?view=vs-2019).

- You can also install the `Ruby` extension in python which will colour your Ruby syntax, for clarity. Click [here](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby) to install the Ruby extension for vsc

### 3. Vagrant 
Vagrant is one way to create and manage a virtual machine, it is the one we are using for this machine, and this is why you need it if you want to interact with this specific machine confuiguration.
- you can install vagrant by following the instructions [here](https://www.vagrantup.com/)

### 4. Virtual Box
Virtual box helps keep track of all your virtual machines, sometimes having it running in the background can prevent certain bugs. 

- To install Virtual Box, please follow [this link](https://www.virtualbox.org/wiki/Downloads) and click on the `hosts` for your operating system. 
- Ensure you are installing version 6.1.16


## How to interact with this machine
1. s