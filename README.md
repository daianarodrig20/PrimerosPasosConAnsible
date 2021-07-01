Voy a utilizar 2 máquinas virtuales con ubuntu como sistema operativo
IPs que voy a utilizar en los ejemplos
- Maquina central: 192.168.101.103
- Nodo: 192.168.101.104

Requerimientos de la máquina central
- Python 2.6+
- Sistema operativo: Red Hat, Debian, CentOS, OS X

Requerimientos del nodo
- Pyhton 2.5+

Instalación de Ansible en Ubuntu
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible

Lo primero que debemos hacer es crear/modificar el fichero /etc/ansible/hosts. En este fichero colocamos el nodo que tenemos de prueba
