# ansible-centos

## ansible 導入

### Mac
```bash
$ brew install ansible
```

## 使い方

```bash
$ ansible-playbook -i "gr.plantdata.net," --ask-pass -u root pd01_add_user_and_init_sshd.yml 
```

```bash
ansible-playbook -i "gr.plantdata.net:20022," --private-key=~/.ssh/pdtec_ecdsa -u pdtec pd01_add_user_and_init_sshd.yml 
```
