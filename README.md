# ASCN


### Correr o deploy
```
ansible-playbook -i inventory/gcp.yml deploy-ghost.yml --ask-vault-pass
```

```
// para o default namespace
kubectl get all
// para outro namespace
kubectl get all -n <nome_do_namespace>
```
