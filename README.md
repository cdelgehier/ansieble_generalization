
Le main include des playbook par servicetype

Le defaults de du playbook sont dans /vars et peut etre surchargée dans l'inventaire (pour all atm)

Les codes ne doit pas levé d'erreur au `yamllint`et au `ansible-lint`

Lancez une partie spécifique :
```
ansible-playbook  main.yml -i inventory_centos.yml -t keystone --diff
```
