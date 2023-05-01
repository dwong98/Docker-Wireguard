# Docker-Wireguard
ITM 684 Docker Wireguard Project
This project is done with the assumption that you have a [DigitalOcean](https://www.digitalocean.com/) account with a droplet running Ubuntu already.

Step 1: [Install Docker]([Install Docker and Docker-Compose on Ubuntu 20.04 (thematrix.dev)](https://thematrix.dev/install-docker-and-docker-compose-on-ubuntu-20-04/))
1. Open up DigitalOcean console. Make sure you are not logged on as the root user.
2. A few thing are needed before installing docker
	1. We need to install the neccessary tools
		 `sudo apt install apt-transport-https ca-certificates curl software-properties-common -y`
	 2. Next comes the Docker key
		 `curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -`
	 3.  Add the Docker Repo (I have 64-bit OS)
Step 2: Setup Wiregurard
