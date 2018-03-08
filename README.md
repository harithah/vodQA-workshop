<p><strong>Windows 10</strong></p>
<p>&nbsp;</p>
<ol>
<li style="font-weight: 400;"><span style="font-weight: 400;">Download and &nbsp;Install Docker.</span></li>
</ol>
<p><a href="https://docs.docker.com/docker-for-windows/install/"><span style="font-weight: 400;">https://docs.docker.com/docker-for-windows/install/</span></a></p>
<p>&nbsp;</p>
<ol start="2">
<li><span style="font-weight: 400;"> Enable Hyper-v and Virtualization </span></li>
</ol>
<ol>
<li style="font-weight: 400;"><span style="font-weight: 400;">Enable virtualization via Bios</span></li>
</ol>
<p><span style="font-weight: 400;">( Search for your laptop specific way to enable virtualization &nbsp;</span></p>
<p><span style="font-weight: 400;"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;and enable via Bios)</span></p>
<p><span style="font-weight: 400;">Example for HP Probook &nbsp;</span></p>
<p><span style="font-weight: 400;">(</span><a href="https://amiduos.com/support/knowledge-base/article/enabling-virtualization-technology-in-hp-systems"><span style="font-weight: 400;">https://amiduos.com/support/knowledge-base/article/enabling-virtualization-technology-in-hp-systems</span></a><span style="font-weight: 400;"> )</span></p>
<ol>
<li><span style="font-weight: 400;"> Enable Hyper-v, Please follow instructions on &nbsp;&nbsp;&nbsp;</span></li>
</ol>
<p><span style="font-weight: 400;"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><a href="https://docs.docker.com/docker-for-windows/troubleshoot/#hyper-v"><span style="font-weight: 400;">https://docs.docker.com/docker-for-windows/troubleshoot/#hyper-v</span></a></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;After Enabling Virtualization and Hyper-v , open task manager and </span></p>
<p><span style="font-weight: 400;"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;virtualization enabled in Performance tab</span></p>
<p><span style="font-weight: 400;"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></p>
<ol start="3">
<li><span style="font-weight: 400;"> Star Docker from the Star menu </span></li>
<li><span style="font-weight: 400;"> Open command prompt and type</span></li>
</ol>
<p><span style="font-weight: 400;">docker --version</span></p>
<p>&nbsp;</p>
<p><strong>Windows 7 and 8</strong></p>
<p>&nbsp;</p>
<ol>
<li style="font-weight: 400;"><span style="font-weight: 400;">Download Docker toolbox from</span></li>
</ol>
<p><a href="https://docs.docker.com/toolbox/toolbox_install_windows/"><span style="font-weight: 400;">https://docs.docker.com/toolbox/toolbox_install_windows/</span></a></p>
<p>&nbsp;</p>
<ol start="2">
<li><span style="font-weight: 400;">Make sure your Windows system supports Hardware Virtualization Technology and that virtualization is enabled.</span></li>
</ol>
<p>&nbsp;</p>
<p><strong>For Windows 8 or 8.1</strong></p>
<p><span style="font-weight: 400;">Choose </span><strong>Start &gt; Task Manager</strong><span style="font-weight: 400;"> and navigate to the </span><strong>Performance</strong><span style="font-weight: 400;"> tab. Under </span><strong>CPU</strong><span style="font-weight: 400;"> you should see the following:</span></p>
<p><span style="font-weight: 400;"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></p>
<p><span style="font-weight: 400;"> &nbsp;&nbsp;&nbsp;&nbsp;</span></p>
<p><strong>For Windows 7</strong></p>
<p><span style="font-weight: 400;">Run a tool like the </span><a href="http://www.microsoft.com/en-us/download/details.aspx?id=592"><span style="font-weight: 400;">Microsoft&reg; Hardware-Assisted Virtualization Detection Tool</span></a><span style="font-weight: 400;"> or </span><a href="https://www.piriform.com/speccy"><span style="font-weight: 400;">Speccy</span></a><span style="font-weight: 400;">, and follow the on-screen instructions. </span></p>
<p>&nbsp;</p>
<ol start="3">
<li><span style="font-weight: 400;"> Verify docker is installed properly</span></li>
</ol>
<p><span style="font-weight: 400;">Open Docker QuickStart icon on Desktop and run:</span></p>
<p><span style="font-weight: 400;"> &nbsp;&nbsp;</span><span style="font-weight: 400;">docker run hello-world</span></p>
<p>&nbsp;</p>
<ol start="4">
<li><span style="font-weight: 400;"> In case of failure open Oracle VM Virtual Box from Desktop and start VM. Now try again the above command.</span></li>
</ol>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">For troubleshooting refer: </span><a href="https://docs.docker.com/toolbox/toolbox_install_windows/#looking-for-troubleshooting-help"><span style="font-weight: 400;">https://docs.docker.com/toolbox/toolbox_install_windows/#looking-for-troubleshooting-help</span></a></p>
<p><br /><br /></p>
<p><strong>Mac OS</strong></p>
<ol>
<li><span style="font-weight: 400;"> &nbsp;Install docker from</span></li>
</ol>
<p><a href="https://docs.docker.com/docker-for-mac/install/"><span style="font-weight: 400;">https://docs.docker.com/docker-for-mac/install/</span></a></p>
<ol start="2">
<li><span style="font-weight: 400;"> The whale in the top status bar indicates that Docker is running, and accessible from a terminal.</span></li>
<li><span style="font-weight: 400;"> Check if docker is setup by running</span></li>
</ol>
<p><span style="font-weight: 400;">docker </span><span style="font-weight: 400;">--version</span></p>
<p>&nbsp;</p>
<p><strong>Get ready for the workshop</strong></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;"> &nbsp;1 . Checkout the workshop code</span></p>
<ol>
<li><em><span style="font-weight: 400;"> mkdir dockerWorkshop</span></em></li>
<li><em><span style="font-weight: 400;">cd</span></em><em><span style="font-weight: 400;"> &nbsp;</span></em><em><span style="font-weight: 400;">dockerWorkshop</span></em></li>
<li><em><span style="font-weight: 400;"> &nbsp;</span></em> <em><span style="font-weight: 400;">git clone</span></em> <a href="https://github.com/harithah/for_workshop.git"><em><span style="font-weight: 400;">https://github.com/harithah/for_workshop.git</span></em></a></li>
<li><em><span style="font-weight: 400;"> git clone</span></em> <a href="https://github.com/harithah/vodQA-workshop.git"><em><span style="font-weight: 400;">https://github.com/harithah/vodQA-workshop.git</span></em></a></li>
<li><em><span style="font-weight: 400;">git clone</span></em> <a href="https://github.com/harithah/ContainerisedTests.git"><em><span style="font-weight: 400;">https://github.com/harithah/ContainerisedTests.git</span></em></a></li>
</ol>
<p>&nbsp;</p>
<p><strong><em>[Install git from </em></strong><a href="https://git-scm.com/downloads"><strong><em>https://git-scm.com/downloads</em></strong></a><strong><em>]</em></strong></p>
<p>&nbsp;</p>
<ol start="2">
<li><span style="font-weight: 400;"> Bringing up the Application.</span></li>
</ol>
<p><span style="font-weight: 400;"> &nbsp;&nbsp;&nbsp;&nbsp;</span><em><span style="font-weight: 400;">&nbsp;cd for_workshop</span></em></p>
<p><em><span style="font-weight: 400;"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;docker-compose up</span></em></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;"> &nbsp;Once the containers are up you access below url in Browser</span></p>
<p><span style="font-weight: 400;">localhost:1313/users/new </span></p>
<p><span style="font-weight: 400;">localhost:1314/addresses/new</span></p>
<p><br /><br /></p>
<p><span style="font-weight: 400;">Yay!!! &nbsp;You are all setup for Docker</span></p>
<p>&nbsp;</p>

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
