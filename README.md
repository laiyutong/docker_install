# Docker_install
Install docker on Kali Linux
<h2>Environment Version</h2>
<img src="https://github.com/laiyutong/docker_install/blob/main/env.png" alt="env" width="70%">

<h2>Installation Steps</h2>
Update the package library before executing.<br>
command：<code>sudo apt update</code><br>
<img src="https://github.com/laiyutong/docker_install/blob/main/1.png" alt="1" width="70%">

Install <a href="https://www.docker.com/">docker.io</a>.<br>
command：<code>sudo apt install -y docker.io</code><br>
<img src="https://github.com/laiyutong/docker_install/blob/main/2.png" alt="2" width="70%">

Start executing docker.<br>
command：<code>sudo systemctl enable docker --now</code><br>
<img src="https://github.com/laiyutong/docker_install/blob/main/3.png" alt="3" width="70%">

<h2>Common commands</h2>
command：<code>docker images</code><br>
<img src="https://github.com/laiyutong/docker_install/blob/main/4.png" alt="4" width="70%">

List and view the list of all running containers.<br>
command：<code>docker ps -a</code><br>
<img src="https://github.com/laiyutong/docker_install/blob/main/5.png" alt="5" width="70%">

<h2>Test</h2>
command：<code>docker run --rm hello-world</code><br>
<img src="https://github.com/laiyutong/docker_install/blob/main/6.png" alt="6" width="70%">
