# Creating Codenvy Account

## Installing `Docker`
1. `wget -qO- https://get.docker.com/ | sh`
	* installs `docker` to the Codenvy environment
2. `sudo groupadd docker`
	* create the docker group
3. `sudo usermod -aG docker $(whoami)`
	* add user to docker group
4. Log out and log back in to ensure that permissions have been modified
5. Ensure `docker` has been installed by executing the following command
	* `docker`
6. `docker run -it eclipse/che start`
	* start the docker service