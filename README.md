# Documentation

This reporsitory contains different documentation on various software engineering topics

# 1. About Multipass
# Multipass summary
&nbsp; This is a summary on how to create an instance of a virtual machine using multipass vm.
- In this session we are going to be talking about some basic commnand in multipass. 
- It is also important you know the basic imortance of using a virtual machine.
&nbsp; **Lets get started** 

To begins you need to install Multipass
-  use the command `sudo apt-get install multipass` to install multipass.
- use `multipass launch <name of instance>` to launch an instance of the machine 
- use `multipass shell <instance> ` to open the shell of your instance on oyur virtual machine.
- use `multipass list` to see the current running  machines or the state of oyur instances you created.
- If you whish to start an instance use `multipass start` followded by the name of the instance
  > For example `multipass start foo`
- To stop the instance use `multipass stop` followed by the name of the instance
  > For example `multipass stop foo`
- Now if i needed to tell you all the other commands that you can use in multipass it will not be able to enter into this page.
- To see the different commands you could use on multipass use the command `multipass help `

## Importance of  using multipass
* ***The following are the importance of using Multiopass***
1.  It helps you to run command that you are scare it might damage your computer.
1. It helps to  run applications that are dangerous or harmful to your machine.
> One of the disavantages of using multipass or virtual machines in general is that it consumes alot of memory as a result computers with less memory cannot run virtual machines with ease.

&nbsp; Now lets talk about containers. 
> A container is  an isolated environment of used to 
run an application and test all its neccessary dependencies and packet managers that can work with the application

A tool used to create a container is called **docker** . Lets now  learn some of the commands use in creating containers using socker.

For more resources on how to use multipass you can visit the following site

[How to use multipass]
(https://multipass.run/)
- The command `multipass exec docker-vm --docker ps` is used to  run a container from your virtual machine on your real machine.
  > Notice that the syntax to run any command on multipass virtual machine is `multipass exec <name of vm> --command `  
- `docker run  hello-world` is used to run the container hello-world either on you virtual machine or on your real machine depending o where you run the command.
- Oh don't forget `docker ps ` is used to see the processing state of your container. 
- To see the different images on your container use `docker images`

  > [For more information about docker visit the following site]
  > (https://www.docker.com/resources/what-container/)
- This documentary was made using markdown.
![The markdown logo] (markdown-mark.png)
