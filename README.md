<h1> Installation instructions</h1>
<h2>Windows 10</h2>

Download and  Install Docker.
	https://docs.docker.com/docker-for-windows/install/ 

     2. Enable Hyper-v and Virtualization 
Enable virtualization via Bios
 		( Search for your laptop specific way to enable virtualization  
                      and enable via Bios)
		Example for HP Probook  
(https://amiduos.com/support/knowledge-base/article/enabling-virtualization-technology-in-hp-systems )
		
                  b. Enable Hyper-v, Please follow instructions on    
              https://docs.docker.com/docker-for-windows/troubleshoot/#hyper-v

         After Enabling Virtualization and Hyper-v , open task manager and 
         virtualization enabled in Performance tab
         
  3. Star Docker from the Star menu 
     4. Open command prompt and type
docker --version

<h2>Windows 7 and 8</h2>

Download Docker toolbox from
	https://docs.docker.com/toolbox/toolbox_install_windows/

     2.    Make sure your Windows system supports Hardware Virtualization Technology and that virtualization is enabled.

For Windows 8 or 8.1
Choose Start > Task Manager and navigate to the Performance tab. Under CPU you should see the following:
         
     
For Windows 7
Run a tool like the Microsoft® Hardware-Assisted Virtualization Detection Tool or Speccy, and follow the on-screen instructions. 

3. Verify docker is installed properly
Open Docker QuickStart icon on Desktop and run:
   docker run hello-world

4. In case of failure open Oracle VM Virtual Box from Desktop and start VM. Now try again the above command.

For troubleshooting refer: https://docs.docker.com/toolbox/toolbox_install_windows/#looking-for-troubleshooting-help


<h2>Mac OS</h2>
1.  Install docker from
https://docs.docker.com/docker-for-mac/install/
2. The whale in the top status bar indicates that Docker is running, and accessible from a terminal.

3. Check if docker is setup by running
docker --version

<h2>Get ready for the workshop</h2>

  1 . Checkout the workshop code
     A. mkdir dockerWorkshop
     B. cd  dockerWorkshop
    C. git clone https://github.com/harithah/for_workshop.git
     D. git clone https://github.com/harithah/vodQA-workshop.git
     E. git clone https://github.com/harithah/ContainerisedTests.git

[Install git from https://git-scm.com/downloads]

  2. Bringing up the Application.
      cd for_workshop
      docker-compose up

  Once the containers are up you access below url in Browser
localhost:1313/users/new 
localhost:1314/addresses/new


Yay!!!  You are all setup for Docker


# Commands to know

docker ps

docker images

docker networks ls

docker inspect <>

docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)
docker ps -a | grep "selenium" | awk '{print $1}' |xargs docker rm -f

docker images -f dangling=true
docker rmi $(docker images -f dangling=true -q)
docker rm $(docker ps -a -f status=exited -q)


docker volume ls

docker volume rm volume_name volume_name

docker volume rm $(docker volume ls -f dangling=true -q)

docker rm -v container_name
