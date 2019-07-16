# foruns-de-votacao

## Pré-requisitos

Instale o pipenv se vc não tiver instalado:

```
pip install pipenv
```

## Instalação e utilização

Baixando projeto, instalando dependência e ativando o ambiente virtual:

```
git clone https://github.com/raymayara/foruns-de-votacao
cd foruns-de-votacao
pipenv install
pipenv shell
```

```
source .env
flask shell
```

Para recriar o banco de dados, digite no shell do flask:


```
from app import db
db.drop_all()
db.create_all()

exit()
```

Por fim, para executar, digite:

```
flask run
```

No navegador acesse [http://127.0.0.1:5000](127.0.0.1:5000)

Para desativar o shell do pipenv digite:

```
deactivate
```
