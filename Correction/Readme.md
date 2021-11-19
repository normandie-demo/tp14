# Correction TP 13


## Créer un Playbook *db.yaml*

```Shell
vi db.yaml
```

## Exécuter le Playbook

```Shell
ansible-playbook -i inventory -v db.yaml --ask-vault-pass
```
