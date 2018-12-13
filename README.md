# Answers to all the Google Code In tasks which I had Completed.

#### My 1st task.(Setup Git)

Git is a popular version control system. We will use them a lot in the course of our tasks.

Follow the instructions here: https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup

*Goals*:
Setup git on your computer. Download and install git on your computer. Instructions vary per operating system. For Linux, you will want to install it from the package manager. For windows and mac, you will want to grab a download from the internet.
Configure your name and email address that you use with FAS/Github etc. Git uses this information to identify commits.

*Deliverables*:
Submit output of git config --get-regexp "user*" Please mask your email addresses such as with asterisks

#### My 2nd task.(Join Fedora Project! Create an account on FAS)
Welcome to the Fedora Project!

The Fedora Account System (FAS) is an authentication and authorization system used in the Fedora Project. Creating a FAS account grants you access to Pagure, Community Blog, Bugzilla and the Fedora Wiki which are required in the subsequent tasks.

https://admin.fedoraproject.org/accounts

*Goals*
Sign up with FAS. Setup your timezone. You must not attach any other field except passwords during registration

*Deliverables*
Submit your FAS id. Your "Account name" is your FAS ID. Please do not attach screenshots or any other document which displays other personal information. If you have done so, please hide/remove it.

https://admin.fedoraproject.org/accounts

### **Note**: These 2 were Beginner task so I am not including the answer.

#### My 3rd task(write a blog on your top 5 most used Ansible module / how you plan to use ansible)

Ansible is open source software that automates software provisioning, configuration management, and application deployment. share ansible knowledge with friends about how you can Ansible to automate few of the things that you do in day to day and focus on modules explanation (briefly). This is to encourage reading about modules in deep and understanding some of the most commonly used modules.

*Goals*:
Write a blog about 5 modules that you have used the most

*Suggested Approach*:
About ansible
module 1
module 2
...
*Deliverables*:
Share blog's link with mentor (vipul@redhat.com)

https://docs.ansible.com/ansible/latest/modules/list_of_all_modules.html

**Solution**: https://nishantparhi.wordpress.com/2018/10/30/top-5-favorite-ansible-module/

#### My 4th task(write a blog on your top 5 most used Ansible module / how you plan to use ansible)

Ansible is open source software that automates software provisioning, configuration management, and application deployment. share ansible knowledge with friends about how you can Ansible to automate few of the things that you do in day to day and focus on modules explanation (briefly). This is to encourage reading about modules in deep and understanding some of the most commonly used modules.

*Goals*
Write a blog about 5 modules that you have used the most

*Suggested Approach*
About ansible

module 1

module 2
...
Deliverables
Share blog's link with mentor (vipul@redhat.com)

https://docs.ansible.com/ansible/latest/modules/list_of_all_modules.html

**Solution**: https://nishantparhi.wordpress.com/2018/10/30/top-5-favorite-ansible-module/

#### My 5th task(write a blog post on 5 favorite vim plugin)

Vim - the ubiquitous text editor Vim is a highly configurable text editor for efficiently creating and changing any kind of text. Vim is usually available by default in most of the operating systems, making it universal. If not available. It can be installed by any package manager. Vim is very powerful and highly extensible. Plugins can be used to make it feel like every other IDE out there. Explore different Plugins and select your top 5 plugins. There are ample amount of youtube videos and blogs on the Internet to help.

*Goal*
A blog post about the plugins that you liked the most

*Suggested approach*
Explore different plugins,
Install them using some package manager (like vundle),
write down the features and how they save time and increase productivity

*Deliverables*
Mail the published post's link to the mentor (vipul@redhat.com)

https://github.com/VundleVim/Vundle.vim

**Solution**: https://nishantparhi.wordpress.com/2018/11/07/top-5-favorite-vim-plugin/

#### My 6th task(write a blog on YML files (explanation and syntax))

YAML is a human-readable data serialization language. It is commonly used for configuration files but could be used in many applications where data is being stored or transmitted.

*Goal*
Research more about it and publish a blog on the medium of your choice.

*Suggested approach*
Follow blogs and youtube videos about YML and understand how to write lists, dictionaries

*Deliverables*
Share blog link with the mentor (vipul@redhat.com)

**Solution**: https://nishantparhi.wordpress.com/2018/11/11/learn-about-yaml-files/

#### My 7th task(Blog post with steps for running Tensorflow GPU on Fedora)

Tensorflow is an open source framework used for mathematical operation, widely used in AI and Machine Learning. It supports heterogeneous computing environments such as CPU, GPU and distributed computing. However, it has a notoriety for being tricky to install.

*Goal*
To verify and make a blog post for the steps for installing TensorFlow libraries (for Python) in Fedora using CUDA for GPU acceleration.

*Requirements*
This will require you to have access to a Fedora system on a device with an NVIDIA GPU.
Proprietary NVIDIA drivers will be required as well.

*Deliverables*
Create a blog post and share it with amitosh@fedoraproject.org
The post can be a Google Docs document, a Word document or a Github Gist written in markdown.

**Solution**: https://nishantparhi.wordpress.com/2018/11/12/running-tensorflow-gpu-on-fedora/

#### My 8th task(Create a playbook and run it on remote nodes)

Ansible is a universal language, unraveling the mystery of how work gets done. Turn tough tasks into repeatable playbooks. Roll out enterprise-wide protocols with the push of a button.

*Goals*
write a playbook to install packages and execute a shell script on remote nodes.

*Steps*
* Create VMs
* Establish passwordless connection
* write playbook
* Record using asciinema

*Deliverables*
Share the asciinema recording

**Solution**: https://github.com/nishantparhi/Remote-nodes

#### My 9th task(Think of an idea to automate a boring job (using Ansible))

Ansible is open source software that automates software provisioning, configuration management, and application deployment. Ansible connects via SSH, remote PowerShell or via other remote APIs. We perform some task that takes a lot of time and is to be done often.

*Goal*
Think of a job that needs automation

*Suggested approach*
think of a task that you have done and has taken a lot of time. Write down the steps you performed during the manual task

*Deliverables*
write a blog and share the idea with a mentor. Mail the blog link to the mentor. (vipul@redhat)

**Solutions**: https://nishantparhi.wordpress.com/2018/11/17/105/

#### My 10th task(Communication over Serial Monitor)

The task can be accomplished in two ways:

* Using the components
* Through simulator (tinkercad.com)

Task:
Read the data from Serial Monitor as ON/OFF and based on which turn the state of LED.
*Components*:
* Arduino/NodeMCU/(any Arduino IDE friendly board)
* LED
* 1 Resistor [320-520 Ohm] (less the resistance bright the intensity, hence no resistance high   intensity which further burns the LED)


*Deliverable*:

* Sketch (code)
* Circuit Diagram
* Constructed Circuit
* Screen-shot of Serial Monitor

**Solution**: https://github.com/nishantparhi/Communication-over-Serial-Monitor

#### My 11th task(DNS-SD demo for Fedora)

mDNS/DNS-SD is a technology used for zero configuration networking. It is widely used in IoT and consumer devices such as Smart TV, printers etc. Our goal is to demo mDNS capabilities of Linux using Avahi.

Goal
Design a mDNS client/server demo using Python. For the client, you can use https://pypi.org/project/zeroconf/. For the server, you can use python-avahi library.

*Bonus points*
* Make a multithreaded server
* Make a client capable for handling multiple servers

*Deliverables*
* A new project on Pagure / GitHub
* Share the project link

**Solution**: https://github.com/nishantparhi/demo-zeroconf

#### My 12th task(Write a custom Ansible module to perform a task)

Ansible has a lot of small modules and one can use them to perform small objectives. The student here needs to write a custom module that will serve a small purpose. It can basically do anything that helps them do some task. Research: Not reinventing the wheel, just for learning purpose. Basic modules like copying a file, changing permissions etc, are small and doable from a new contributor. This is just for learning purpose.

*Goal*
To write a module that can be used in ansible

*Suggested approach*
* Figure out a small goal
* Understand how ansible works and how it handles modules
* Find blogs that cover ansible module writing
* Come up with a $operation.py module

*Deliverables*
Put the module in a github repo and share the link with the mentor (vipul@redhat.com)

https://docs.ansible.com/ansible/latest/modules/modules_by_category.html

**Solution**: https://github.com/nishantparhi/my_ansible_module

#### My 13th task(Write ansible roles to install & update packages)

Ansible is a universal language, unraveling the mystery of how work gets done. Turn tough tasks into repeatable playbooks. Roll out enterprise-wide protocols with the push of a button.

*Goal*
Write an Ansible role to

* Install any 3 packages
* update 3 packages

*Deliverables*
Put it in a repo and share the link in a repo

**Solution**: https://github.com/nishantparhi/install-update-role

#### My 14th task(Install jenkins in a container)

Containers are awesome. This task will teach you how you can download and run Jenkins in a container. To start with we will use Docker, visit Jenkins' official site. Combining Jenkins and Docker together can bring improved speed and consistency to your automation tasks.

*Goals*
install jenkins in a container

*Suggested approach*
Follow the official guide

*Deliverables*
Screenshot of terminal running docker and browser's

https://jenkins.io/doc/book/installing/#downloading-and-running-jenkins-in-docker

**Solution**:https://github.com/nishantparhi/Shell-Jenkins

#### My 14th task(Write a blog on steps to execute a shell script from Jenkins)

The leading open source automation server, Jenkins provides hundreds of plugins to support building, deploying and automating any project. Read from https://www.cloudbees.com/sites/default/files/cje-study-guide-2018.pdf and brief about important topics.

*Goal*
To execute a shell script from Jenkins

*Steps*
write a shell script to delete all the lines from a file that has a word 'status' in it. Execute that shell script through Jenkins

*Deliverables*
Put the shell script in a repo and steps on a README, share link with the mentor (vipul@redhat.com)

**Solution**: https://github.com/nishantparhi/Ansible-in-jenkins

#### My 15th task(Blog post with steps for running OpenCV on Fedora)

OpenCV (Open Source Computer Vision) is a library of programming functions mainly aimed at real-time computer vision. It sees wide use in AI applications. However, it has a notoriety for being tricky to install.

*Goal*
To verify and make a blog post for the steps for installing OpenCV (C++ and Python) libraries in Fedora.

*Deliverables*
Create a blog post and share it with amitosh@fedoraproject.org
The post can be a Google Docs document, a Word document or a Github Gist written in markdown.

**Solution**: https://nishantparhi.wordpress.com/2018/11/25/running-opencv-on-fedora/

#### My 16th task(Blog post with steps for running Tensorflow on Fedora)

Tensorflow is an open source framework used for mathematical operation, widely used in AI and Machine Learning. It supports heterogeneous computing environments such as CPU, GPU and distributed computing. However, it has a notoriety for being tricky to install.

*Goal*
Verify and make a blog post for the steps for installing TensorFlow libraries (for Python) in Fedora.

*Deliverables*
Create a blog post and share it with amitosh@fedoraproject.org
The post can be a Google Docs document, a Word document or a Github Gist written in markdown.

**Solution**:https://nishantparhi.wordpress.com/2018/11/25/running-tensorflow-on-fedora/

#### My 17th task(Blog post with steps for booting Fedora from a PXE server)

Bootstrapping a Fedora installation from a PXE server (also called as a network boot) is a non-trivial task. We seek to provide a proper guide for doing such.

*Requirements*
This task requires comfortable skills with BIOS and basic network knowledge such as IP addresses.

*Goals*
To create a guide for Fedora network boot. It should cover topics such as setting up an install server using cobbler, configuring the DHCP and the system BIOS.

*Deliverables*
Create a blog post and share it with amitosh@fedoraproject.org
The post can be a Google Docs document, a Word document or a Github Gist written in markdown.
https://docs.fedoraproject.org/en-US/Fedora/13/html/Installation_Guide/sn-booting-from-pxe-x86.html

**Solution**:https://nishantparhi.wordpress.com/2018/11/25/booting-fedora-from-a-pxe-server/

#### My 18th task(Execute ansible playbook from Jenkins using Ansible plugin)

The leading open source automation server, Jenkins provides hundreds of plugins to support building, deploying and automating any project. Read from https://www.cloudbees.com/sites/default/files/cje-study-guide-2018.pdf

Ansible is open source software that automates software provisioning, configuration management, and application deployment. Ansible connects via SSH, remote PowerShell or via other remote APIs.

*Goal*
To execute an Ansible playbook from Jenkins

*Steps*
* Write a playbook
* Install Ansible plugin in Jenkins
* Trigger the job

*Deliverables*
Put the console output and Ansible playbook in a repo and steps on a README, share the link with the mentor (vipul@redhat.com)

**Solution**:https://github.com/nishantparhi/Ansible-in-jenkins

#### My 19th task(Create dynamic inventory (Ansible) using Jinja2 templates)

*Goal*
To create an inventory file using ansible template feature

*Suggested approach*
* pass variable in command using flag -e
* use jinja2 to define the structure to the inventory file
* use template module to pass variable to j2 files and create inventory

*Deliverables*
Share j2 file and the playbook in a repo/gist and mail the link to the mentor (vipul@redhat.com)

**Solution**:https://github.com/nishantparhi/Dynamic-inventory 

#### My 20th task(Connecting with the internet -GET the time)

In order to communicate over any network you either transmit or receive the data. In this task, you have to receive the data using an API.

You have to connect your board to the internet (preferably through WiFi). Then make an API of any website which provides you time in your local time-zone. You have to send a GET request, and read the time and print it on the Serial Monitor/Terminal.

*Preferred Boards*: NodeMCU | Raspberry PI | Arduino + ESP8266

*Deliverable*: The sketch (code), the circuit diagram (if you have used any external module to connect) and API link.

**Solution**:https://github.com/nishantparhi/Get-Time

#### My 21st task(Automate a job using Ansible that has been taking your time.)

*Goal*
Think of a job that needs automation and automate it

*Suggested approach*
Finish task 5254136867061760 Gather information on modules to be used and automate it

*Deliverables*
Share the playbook/roles in a repo and mail the repo link to the mentor. (vipul@redhat)

**Solution**: https://github.com/nishantparhi/Automate-timetaking-task

#### My 22nd task(Getting started with Arduino)

The entire task is divided into two subtasks: Setting up the board for NodeMCU; and Interfacing and changing the brightness of an LED.

*Requirements*:

Arduino (any board)/NodeMCU (any board from ESP8266 family) LED 1 Resistor [320-520 Ohm] (less the resistance bright the intensity, hence no resistance high intensity which further burns the LED)

*Task*:

Install the Arduino IDE on Fedora; Set up the IDE for NodeMCU board; Add the library for DHT11, ESP8266WiFi and ESP8266HTTPClient;

Interface an LED and change the brightness of the LED (print this on the Serial Monitor indicating the analog Values);

*Deliverable*:

Screen-shot of your installation; Screen-shot of the board which shows the option for NodeMCU board; Screen-shot of Include Library from tools which shows the option for the required Libraries; Sketch (code) for varying LED brightness; Screenshot of the Serial Monitor.

**Solution**: https://github.com/nishantparhi/Intro-to-arduino

#### My 23rd task(Blog post about booting a Fedora ARM image to Raspberry PI)

Fedora is a Linux distribution developed by the community-supported Fedora Project and sponsored by Red Hat. Fedora contains software distributed under various free and open-source licenses and aims to be on the leading edge of such technologies. Raspberry Pi is an ARM-based mini computer used for prototyping embedded computing projects. The Fedora ARM installer is a quick and easy way to prepare an SD card with a Fedora image that is bootable on a Raspberry PI.

*Note*:

You must try this in a real Raspberry Pi (any version) and add the screenshots.
You must not submit plagiarized content (no copy-paste). Always make sure the content is your own.

*Goals*
Verify the steps and prepare a blog post for creating a Fedora Raspberry Pi bootable SD card.

*Deliverables*
Create a blog post and share it here
The post can be a Google Docs document, a Word document or a Github Gist written in markdown.

**Solution**:https://nishantparhi.wordpress.com/2018/12/05/booting-fedora-arm-image-to-raspberry-pi/

#### My 24th task(Automate release validation in Fedora)

The leading open source automation server, Jenkins provides hundreds of plugins to support building, deploying and automating any project. Read from https://www.cloudbees.com/sites/default/files/cje-study-guide-2018.pdf

Ansible is open source software that automates software provisioning, configuration management, and application deployment. Ansible connects via SSH, remote PowerShell or via other remote APIs.

*Goal*
To automate Fedora release validation using Jenkins and Ansible

*Steps*
* Write a playbook/role automating release validation steps to get steps, go to https://www.happyassassin.net/testcase_stats/29/, select OS, select any one test.
* Install Ansible plugin in Jenkins
* Trigger the job on the latest available image

*Deliverables*
Share the role in a GitHub repo with the mentor (vipul@redhat.com)

**Solution**:https://github.com/nishantparhi/Automate-Release-Validation

#### My 25th task(Automation using Ansible)

Automate https://fedoraproject.org/wiki/QA:Testcase_base_service_manipulation using ansible (roles).

* Take some other daemon instead of sshd and put it in a variable so that it can be changed/more services can be added later.

* Submit the link to a repo with a playbook and the roles.

https://fedoraproject.org/wiki/QA:Testcase_base_service_manipulation

**Solution**: https://bitbucket.org/nishantparhi/automation-using-ansible/src/master/

#### MY 26th task(Use Keybindings for 5 Plugins/Actions)

Vim - the ubiquitous text editor Vim is a highly configurable text editor for efficiently creating and changing any kind of text. Vim is usually available by default in most of the operating systems, making it universal. If not available. It can be installed by any package manager. Vim is very powerful and highly extensible. Plugins can be used to make it feel like every other IDE out there. Explore different Plugins and select your top 5 plugins. There are ample amount of youtube videos and blogs on the Internet to help.

*Goal*
Use keybindings to change atleast 5 default keys for plugins

*Suggested approach*
* Learn how to bind keys
* Modify vimrc

*Deliverables*
Mail vimrc file's link to the mentor (vipul@redhat.com) vimrc file should be in a repo

**Solution**: https://github.com/nishantparhi/Vimrc-configuration/blob/master/vimrc

#### My 27th task(Design a New Home Screen for Fedora App)

Introduction - We have a Fedora Community Application that allows Fedora users as well as interested contributors to know what’s going on in the community. The current home screen houses a split screen design with carousel, it is not really intuitive to the new users, and we believe it can be simplified.

*Goal* - Design a new home screen for the Fedora App

*Suggested Approach* - List down all the features which we should show on the home screen and experiment with different layouts. Post them on Pagure issue and we will collectively figure out something

*Deliverables* - Images of the new home screen design with complete flow Create a PR on Pagure once done.

Reach out to thelittlewonder@fedoraproject.org if you have any doubts.

https://pagure.io/Fedora-app/issue/115

**Solution**:
![](design1st.png)
![](Design2nd.png)