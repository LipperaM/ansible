# Enter venv

```
  source .venv/bin/activate
```


## Check venv

```
  which pip
```


# Interact with Ansible with root password

```
  ansible-playbook playbooks/bootstrap.yml -k -v
```

# Interact with Ansible with admin user

```
  ansible-playbook playbooks/some-playbook.yml  
```

# Close venv

```
  deactivate
```
