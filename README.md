<h1><strong>Installation instructions</strong></h1>
<h2><a id="user-content-windows-10" class="anchor" href="https://github.com/harithah/vodQA-workshop/blob/master/README.md#windows-10" aria-hidden="true"></a><strong>Windows 10</strong></h2>
<p>&nbsp;</p>
<ol>
<li>Download and &nbsp;Install Docker.</li>
</ol>
<p><a href="https://docs.docker.com/docker-for-windows/install/" rel="nofollow">https://docs.docker.com/docker-for-windows/install/</a></p>
<ol start="2">
<li>Enable Hyper-v and Virtualization <br />a. Enable virtualization via Bios</li>
</ol>
<p>( Search for your laptop specific way to enable virtualization&nbsp;and enable via Bios)</p>
<p>Example for HP Probook &nbsp;</p>
<p>(<a href="https://amiduos.com/support/knowledge-base/article/enabling-virtualization-technology-in-hp-systems" rel="nofollow">https://amiduos.com/support/knowledge-base/article/enabling-virtualization-technology-in-hp-systems</a> )</p>
<p>&nbsp; &nbsp; &nbsp; &nbsp;b. Enable Hyper-v, Please follow instructions on &nbsp; &nbsp;</p>
<p><a href="https://docs.docker.com/docker-for-windows/troubleshoot/#hyper-v" rel="nofollow">https://docs.docker.com/docker-for-windows/troubleshoot/#hyper-v</a></p>
<p>&nbsp;</p>
<p>After Enabling Virtualization and Hyper-v , open task manager and&nbsp;virtualization should be enabled in Performance tab</p>
<p>&nbsp; &nbsp; &nbsp; &nbsp;&nbsp;</p>
<ol start="3">
<li>Star Docker from the Star menu</li>
<li>Open command prompt and type</li>
</ol>
<p>docker --version</p>
<p>&nbsp;</p>
<h2><a id="user-content-windows-7-and-8" class="anchor" href="https://github.com/harithah/vodQA-workshop/blob/master/README.md#windows-7-and-8" aria-hidden="true"></a><strong>Windows 7 and 8</strong></h2>
<p>&nbsp;</p>
<ol>
<li>Download Docker toolbox from</li>
</ol>
<p><a href="https://docs.docker.com/toolbox/toolbox_install_windows/" rel="nofollow">https://docs.docker.com/toolbox/toolbox_install_windows/</a></p>
<p>&nbsp;</p>
<ol start="2">
<li>Make sure your Windows system supports Hardware Virtualization Technology and that virtualization is enabled.</li>
</ol>
<p>&nbsp;</p>
<p><strong>For Windows 8 or 8.1</strong></p>
<p>Choose <strong>Start &gt; Task Manager</strong> and navigate to the <strong>Performance</strong> tab. Under <strong>CPU</strong> you should see the virtualization enabled.</p>
<p>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;&nbsp;</p>
<p><strong>For Windows 7</strong></p>
<p>Run a tool like the <a href="http://www.microsoft.com/en-us/download/details.aspx?id=592" rel="nofollow">Microsoft&reg; Hardware-Assisted Virtualization Detection Tool</a> or <a href="https://www.piriform.com/speccy" rel="nofollow">Speccy</a>, and follow the on-screen instructions.</p>
<p>&nbsp;</p>
<ol start="3">
<li>Verify docker is installed properly</li>
</ol>
<p>Open Docker QuickStart icon on Desktop and run:</p>
<p>&nbsp;&nbsp;docker run hello-world</p>
<p>&nbsp;</p>
<ol start="4">
<li>In case of failure open Oracle VM Virtual Box from Desktop and start VM. Now try again the above command.</li>
</ol>
<p>&nbsp;</p>
<p>For troubleshooting refer: <a href="https://docs.docker.com/toolbox/toolbox_install_windows/#looking-for-troubleshooting-help" rel="nofollow">https://docs.docker.com/toolbox/toolbox_install_windows/#looking-for-troubleshooting-help</a></p>
<p><br /><br /></p>
<h2><a id="user-content-mac-os" class="anchor" href="https://github.com/harithah/vodQA-workshop/blob/master/README.md#mac-os" aria-hidden="true"></a><strong>Mac OS</strong></h2>
<ol>
<li>&nbsp;Install docker from</li>
</ol>
<p><a href="https://docs.docker.com/docker-for-mac/install/" rel="nofollow">https://docs.docker.com/docker-for-mac/install/</a></p>
<ol start="2">
<li>The whale in the top status bar indicates that Docker is running, and accessible from a terminal.</li>
<li>Check if docker is setup by running</li>
</ol>
<p>docker --version</p>
<p>&nbsp;</p>
<h2><a id="user-content-get-ready-for-the-workshop" class="anchor" href="https://github.com/harithah/vodQA-workshop/blob/master/README.md#get-ready-for-the-workshop" aria-hidden="true"></a><strong>Get ready for the workshop</strong></h2>
<p>&nbsp;Create an account at:</p>
<p><a href="https://hub.docker.com/">https://hub.docker.com/</a></p>
<p>Once you are done run the command:</p>
<p>docker login</p>
<p>Supply username and password</p>
<p>&nbsp;1 . Checkout the workshop code</p>
<ol>
<li><em> mkdir dockerWorkshop</em></li>
<li><em>cd</em><em> &nbsp;</em><em>dockerWorkshop</em></li>
<li><em> &nbsp;</em> <em>git clone</em> <a href="https://github.com/harithah/for_workshop.git"><em>https://github.com/harithah/for_workshop.git</em></a></li>
<li><em> git clone</em> <a href="https://github.com/harithah/vodQA-workshop.git"><em>https://github.com/harithah/vodQA-workshop.git</em></a></li>
<li><em>git clone</em> <a href="https://github.com/harithah/ContainerisedTests.git"><em>https://github.com/harithah/ContainerisedTests.git</em></a></li>
</ol>
<p>&nbsp;</p>
<p><strong><em>[Install git from </em></strong><a href="https://git-scm.com/downloads" rel="nofollow"><strong><em>https://git-scm.com/downloads</em></strong></a><strong><em>]</em></strong></p>
<p>&nbsp;</p>
<ol start="2">
<li>Bringing up the Application.</li>
</ol>
<p>&nbsp;&nbsp;&nbsp;&nbsp;<em>&nbsp;cd for_workshop</em></p>
<p><em> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;docker-compose up</em></p>
<p>&nbsp;</p>
<p>&nbsp;Once the containers are up you access below url in Browser</p>
<p>localhost:1313/users/new</p>
<p>localhost:1314/addresses/new</p>
<p><br /><br /></p>
<p>Yay!!! &nbsp;You are all setup for Docker</p>
<p>&nbsp;</p>
<h2>Commands to know</h2>
<p>docker ps</p>
<p>docker images</p>
<p>docker networks ls</p>
<p>docker inspect &lt;&gt;</p>
<p>docker stop $(docker ps -a -q) docker rm $(docker ps -a -q) docker ps -a | grep "selenium" | awk '{print $1}' |xargs docker rm -f</p>
<p>docker images -f dangling=true docker rmi $(docker images -f dangling=true -q) docker rm $(docker ps -a -f status=exited -q)</p>
<p>docker volume ls</p>
<p>docker volume rm volume_name volume_name</p>
<p>docker volume rm $(docker volume ls -f dangling=true -q)</p>
<p>docker rm -v container_name</p>
