## Git Commands:
git clone -> To clone remote git repository to local system
git pull -> To pull from remote to local repositories
git status -> to check files that’s been modified in local
git diff -> to view all modifications in local
git add . -> to commit changes of all files in local
git add file_name1  file_name2 -> to commit specific files in local
git commit -m "commit message" -> to commit in local
git log -> to verify the commit
git push -> to push from local to remote
Branch:
	Main / Master: default branch (complete code)
	Each feature will have separate branch.
git checkout -b git-branch: to create and switch to new branch 'git-branch'
Git pull origin branch-name2 : pull from other branch (branch-name2) to your branch
Git checkout branch-name : to switch to a different branch
Git push -u origin git-branch : to push from local branch to remote master

## Vagrant Commands:
Tool to create virtual machines using automation
Vagrant up: To make VM up
Vagrant ssh: To connect to VM
Vagrant halt: To halt vagrant VM
vagrant down: TO remove VM
systemctl status jenkins: To check if Jenkins is running or not \n
sudo su - jenkins : to switch to jenkins user
ssh-keygen: creates rsa key pair. Add public key in github. private key in jenkins.
ssh-keyscan github.com >> ~/.ssh/known_hosts : to add git hub to known hosts.

## Docker Commands:
docker pull image_name:tag_name -> to pull docker image from docker hub or repository
docker run image_name:tag_name -> to create and strt container using images (containers will be dead after the run completed)
docker ps -> shows running containers
docker ps -a -> shows both running containers and dead containers
docker stop container_name -> to stop container
docker rm container_name -> to remove a container
docker create image_name -> to create a container but not starting
docker start container_name -> to start a container

## nginx Commands with docker:
docker run -p 8080:80 image_name -> to run nginx image (-p is for port mapping from 80 to 8080, 80 is default port)
docker run -d -p 8080:80 image_name -> to run the nginx in backgroung (-d is for detach mode (background))
