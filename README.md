# BURP - DOCKER - GUI - WINDOWS HOST - LINUX CONTAINERS

Solution based on: https://www.marcolancini.it/2018/blog-docker-burp/ and https://github.com/alpin3/burpfree

Powershell (As Administrator)
1. Run xserverWindows.ps1 (in case of first start)
2. It's important to set up environment variable $env:LOCAL_IP 
	(you can do that by executing xserverWindows.ps1 or getIP.ps1) 
3. Run Xlaunch and save configuration likewise in this article: https://dev.to/darksmile92/run-gui-app-in-linux-docker-container-on-windows-host-4kde
   (choco install has been made by xserverWindows.ps1 script)
4. Start services: `docker-compose up`
