



```
ansible-playbook  --private-key=~/Downloads/xxx.pem -u ubuntu  -i Debian/debianhosts  Debian/playbooks/solution.yaml 
```

You can watch `netstat` on one of the hosts, look for 5000 open and close. 
```
watch netstat -tulpn
```
