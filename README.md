# ansible-nginx
use ansible deployment nginx

    ├── roles
    │   └── nginx
    │       ├── files
    │       │   └── index.html
    │       ├── handlers
    │       │   └── main.yaml
    │       ├── tasks
    │       │   └── main.yaml
    │       ├── templates
    │       │   └── nginx.conf.j2
    │       └── vars
    │           └── main.yaml
    └── site.yaml

# 安装命令
ansible-playbook -i host site.yaml
