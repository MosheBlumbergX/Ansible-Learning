
```
ansible-vault encrypt inventory.txt

ansible-playbook playbook -i inventory.txt # fail with can't decrypt 

ansible-playbook playbook -i inventory.txt -ask-vault-pass # asks for password

ansible-playbook playbook -i inventory.txt -vault-password-file ~/.vault-file # read pass from file 

ansible-playbook playbook -i inventory.txt -vault-password-file ~/.vault-file.py # replace password stored plaintext file, script can take a password. 

ansible-vault view inventory.txt

ansible-vault create inventory.txt

```