# Instructions
## Startup instructions

1. ansible-playbook -i hosts ~/kube-cluster/initial.yml
2. ansible-playbook -i hosts ~/kube-cluster/kube-dependencies.yml
3. ansible-playbook -i hosts ~/kube-cluster/master.yml
4. ansible-playbook -i hosts ~/kube-cluster/workers.yml

## Inspection instructions
1. ssh ubuntu@master_ip
2. kubectl get nodes 
