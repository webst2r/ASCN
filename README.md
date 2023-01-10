## :cloud: 💻 Aplicações e Serviços de Computação em Nuvem


### Correr o deploy
```
ansible-playbook -i inventory/gcp.yml deploy-ghost.yml --ask-vault-pass
```
### Listar todos os pods, serviços, etc. num namespace
```
// para o default namespace
kubectl get all
// para outro namespace
kubectl get all -n <nome_do_namespace>
```

### Ativar APIs de monitoring
gcloud services enable monitoring --project=ascn-tp-g17

gcloud services enable compute.googleapis.com
gcloud services enable monitoring.googleapis.com
gcloud services enable cloudbuild.googleapis.com 
