# practice-ansible

Tranfers rsa_id.pub to subservent machine. Must know the password of subservent machine.
```javascript 
ssh-copy-id <USER_NAME>@<IP_ADDRESS>
```
Allow a user to run commands without sudo
```javascript
user_name ALL=(ALL) NOPASSWD:ALL
```
