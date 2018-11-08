# Deuxième atelier

Les concepts couvert :

* La structure Ansible des rôles
* Appel d'un rôle dans notre playbook


## Préparation

On va avoir besoin de se connecter en SSH à la machine local.
Pour cela, on va installer le server SSH et configurer notre machine:

```
sudo apt-get install openssh-server
cp ~/.ssh/id_rsa.pub ~/.ssh/authorized_keys
```
