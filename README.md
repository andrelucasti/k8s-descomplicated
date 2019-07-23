# Welcome!

This repository is my studys to be a expert in kubernetes, if you search to be  expert in kubernetes too, weeelcomeee!!! Annndd have fun !

### Vagrantfile
I made a file Vagrantfile which contains three machine to create the cluster for you to study kubernetes. So follow the steps down.

1. Install virtualbox
2. Install vagrant
3. clone this repository
 
### My kubernetes cluster

So after the last steps, finish time to create your kubernetes cluster:

1. Install docker
2. Install kubernetes
3. Initializer Master Node: 
`kubeadm init --apiserver-advertise-address=$IP_ADDR --apiserver-cert-extra-sans=$IP_ADDR --node-name $HOST_NAME --pod-network-cidr=192.168.0.0/16`