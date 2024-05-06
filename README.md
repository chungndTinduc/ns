Update package lists
- apt-get update

Install Git
- apt-get install -y git
  
Install Docker
- apt-get install -y docker.io 

Add permisstion folder
- sudo chmod o+rx docker_mssql_data/

Install PowerShell Core
- wget -q https://packages.microsoft.com/config/ubuntu/$ (lsb_release -rs)/packages-microsoft-prod.deb -O packages-microsoft-prod.deb dpkg -i packages-microsoft-prod.deb apt-get update apt-get install -y powershell

Remove folder
- sudo mv /home/duthao/data /var/lib/docker/volumes/docker_mssql_data/_data/
- 
- docker volume ls docker volume inspect docker_mssql_data
- sudo du -h --max-depth=1 /var/lib/docker
- docker system df
- df -h
