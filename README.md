# nhproject
You will need to install software on your computer. If you are using windows, you can use chocolatey for software instalation.
To install chocolatey in windows OS:
1. Open powershell as an administrator
2. With PowerShell, you must ensure Get-ExecutionPolicy is not Restricted. We suggest using Bypass to bypass the policy to get things installed or AllSigned for quite a bit more security.
3. Run the following command in powershell: Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
4. If you don't see any errors, you are ready to use Chocolatey! Type choco or choco -? (https://chocolatey.org/install)

choco install virtualbox 
choco install vagrant 
choco install git 
choco install jdk8
choco install maven 
choco install awscli
choco install intellijidea-community
choco install sublimetext3.app

About the project: 
Multi Tier Web Application Stack
Setup on Laptop/Computer 
Baseline for Upcoming projects

Architecture of project: 
NGINX 
TOMCAT
RABBITMQ
MEMCACHED
MYSQL
