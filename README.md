Commands:

- chmod (without sudo) (chmod 600 /home/catarina/.ssh/cvrnogueira.pem )
- create keyvalue on AWS (if there was no one, but I've already created)
- if there is no ssh on home/user folder : (mkdir  ~.ssh)
- put .pem on this .ssh folder (.pem was downloaded from AWS keyvalue, is on my computer)
- ssh-agent bash 
- ssh-add ~/.ssh/keypair.pem (ssh-add /home/catarina/.ssh/cvrnogueira.pem)
- ansible-playbook -i hosts --ask-vault-pass playbook.yml -v

