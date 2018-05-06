# To Run

```
ansible-playbook --ask-sudo-pass -i production play.yml
```

# What is it?

The infrastructure for my sites.

It's roughly laid out like this

```
Ansible -> Reverse proxy -> Containers 
```

Containers are stored in separate repositories and contain everything they need.
