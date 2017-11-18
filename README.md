# ansible_shadowsocks
ansible 部署 shadowsocks

本机使用:
```bash
ansible-playbook ss.yml -c local  -i "localhost,"
```

远程服务器:
```bash
ansible-playbook ss.yml -i inventory.ini

```