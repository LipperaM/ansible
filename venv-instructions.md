# Enter venv

```
  source .venv/bin/activate
```


## Check venv

```
  which pip
```


# Interact with Ansible

```
  ansible-playbook playbooks/site.yml -i inventory/hosts.ini --ask-vault-pass
  ansible-vault edit vault.yml
  ansible-vault create vault.yml
```

# Close venv

```
  deactivate
```
