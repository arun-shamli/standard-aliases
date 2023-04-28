install guest tools

## install git
sudo add-apt-repository ppa:git-core/ppa
sudo apt update; sudo apt install git

git config --global user.name "Arun Kumar"
git config --global user.email "arun.shamli@gmail.com"

## Python
install anaconda

## docker and minikube
- install docker ( get the instructions from docker.com)
- install minikube
  
  ```
  curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube_latest_amd64.deb
  sudo dpkg -i minikube_latest_amd64.deb
  ```
## install kubenx utility
git clone https://github.com/ahmetb/kubectx.git ~/.kubectx
COMPDIR=$(pkg-config --variable=completionsdir bash-completion)
sudo ln -sf ~/.kubectx/completion/kubens.bash $COMPDIR/kubens
sudo ln -sf ~/.kubectx/completion/kubectx.bash $COMPDIR/kubectx
cat << EOF >> ~/.bashrc


#kubectx and kubens
export PATH=~/.kubectx:\$PATH
EOF

## install packages
- sudo apt install net-tools
- sudo apt install make
- sudo apt install openssh-server
- sudo apt install pkgconf
- docker pull ubuntu
- docker image inspect ubuntu










install kubectl

install linkerd

#install local package
sudo apt install ./name.deb or sudo dpkg -i ./name.deb



docker volume create portainer_data
docker run -d -p 8000:8000 -p 9443:9443 --name portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce:latest
portainer password : srishti1!singh

install edge, visual studio code, sublime text

color blue = rgb(75, 174, 229)
