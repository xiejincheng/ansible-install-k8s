# v1.16
## 1、修改hosts文件
## 2、修改group_vars/all.yml文件
## 3、部署
### 高可用集群版：ansible-playbook -i hosts ha-deploy.yml -uroot -k
### 单Master版：ansible-playbook -i hosts single-master-deploy.yml -uroot -k
