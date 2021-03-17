## Instalação do gerenciado pacote python
```sh
https://python-poetry.org/docs/#installation
```

## Criando projeto django com ansible

```sh
# Inicia um projeto
poetry init -n

# Entra no ambiente virtual
poetry shell

# Instala biblioteca necessária para rodas aplicação
poetry add ansible
```


## Rodando o django 2.2.19 lts
```sh
cd django2-lts
ansible-playbook playbook_deploy.yml


## acesse maquina remoto
cd ~/projects/myproject2
poetry shell
./manage.py runserver
./manage.py makemigrations
./manage.py migrate
```


## Rodando o django 3.1.7
```sh
cd django3
ansible-playbook playbook_deploy.yml

```

## acesse maquina remoto
```sh
cd ~/projects/myproject3
poetry shell
./manage.py runserver
./manage.py makemigrations
./manage.py migrate
```


