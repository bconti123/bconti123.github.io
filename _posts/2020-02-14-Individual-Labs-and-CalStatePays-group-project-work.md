---
post: Individual Labs and CalStatePays Group Project Work

---

February 10, 2020 to February 13, 2020

EC2 Labs are very good to be learning about deploying and installing Windows Server and Linux. I never thought about “User data, select As text”! Next time, I will not need to type command line in EC2 instance as Linux because creating EC2 instance and the script in user data as text will do install apache server at the same time. Maybe, you could add “get-apt update && get-apt upgrade” in user data as text is good idea? I never try it out before. I will do it next time! EC2 Windows Lab instruction is very old because it wants me to install Windows Server 2012. I already know how to use Windows Server 2012. I read slack that my professor said Windows Server 2019 is the best bet to try. I tried to deploy and install Windows Server 2019 in EC2 instance. I didn’t understand IIS server is not installed yet. I did copy and paste the text in user data as text from Windows Lab instruction. Windows Server 2019 is very slow to use because EC2 instance has low RAM and weak CPU. I was patience with it. I tried to troubleshoot IIS server installation in user data as text box. I copied and pasted the text from the instruction lab then tested PowerShell command line window in EC2 Windows Server 2019. It gave error because the text is for Windows Server 2012. I researched that how to install IIS server in command line for Windows Server 2019. I corrected the command line in user data as text for Windows Server 2019.I added “—name” before “Web-Server…”. See this below.
In EC2 Windows Lab

For Windows Server 2012 this below:

<powershell>Install-WindowsFeature Web-Server -IncludeManagementTools -IncludeAllSubFeature</powershell>

For Windows Server 2019 this below:

<powershell>Install-WindowsFeature –name Web-Server -IncludeManagementTools -IncludeAllSubFeature</powershell>

CalStatePays project, we divided work role. My partner and I will responsible for the calculating the prices for On-Demand Instances, Reserved Instances, and Spot Instance to determine which is cheaper than the current on-premise windows server running in CSUN, which is CalStatePays. I was trying to find good pricing calculator on the AWS server and compare with different instance type. Creating spreadsheet is a lot of work! I will try do my best. We will find better one is cheaper then replace the current on-premise windows server.
