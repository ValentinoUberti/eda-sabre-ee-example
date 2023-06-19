# Prerequisites

```
pip install ansible-rulebook ansible ansible-runner
```

# Galaxy collection

- https://galaxy.ansible.com/sabre1041/eda

```
ansible-galaxy collection install sabre1041.eda
```


## Run in a terminal

```
ansible-rulebook -i inventory --rulebook rulebook.yml --verbose 
```
