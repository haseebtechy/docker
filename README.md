# How to Install Docker in Ubuntu 18.04 LTS
### To install Docker on Ubuntu 18.04 LTS, follow these steps:

- Update the apt package index:

- ` sudo apt-get update`

- Install the necessary packages to allow apt to use a repository over HTTPS:
- `sudo apt-get install apt-transport-https ca-certificates curl gnupg-agent software-properties-common`

- Add Docker’s official GPG key:
- ` curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -`

- Add the Docker repository to your system:
- `sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"`

- Update the apt package index again:
- `sudo apt-get update`

Install the latest version of Docker:
- `sudo apt-get install docker-ce docker-ce-cli containerd.io`

Check that Docker is installed correctly by running the hello-world container:
- `sudo docker run hello-world`

- That's it! You now have Docker installed on your `Ubuntu 18.04 LTS` machine.



