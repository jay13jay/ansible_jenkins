# ansible_jenkins
ansible deployment for jenkins server

### Depends
depends on having user admin on your server and hostname located in vars/var.yaml
##### alternatively (not rec)
just change the 'installJenkins.yaml' file to the root user and update your inventory appropriately


# for Brainfock PM:
### Depends:
- access to your github account, so use a key
- generate an RSA keypar (I use ssh-keygen on linux/osx)
- make sure private key is on the server you want to install on
- make sure public key is added to your github (alternatively just add your pub key to github)
