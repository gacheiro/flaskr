# Flaskr
Seguindo o [tutorial](http://flask.pocoo.org/docs/0.12/tutorial) do flask de um mini blog.

# Instalar

Crie um ambiente virtual

```python3 -m venv venv```

Com o ambiente virtual ativo, instale o flaskr no modo editável:

```pip install --editable .```

# Rodando o app

Defina as variáveis de ambiente:

```
export FLASK_APP=flaskr
export FLASK_DEBUG=true
```

Se for Windows:

```
set FLASK_APP=flaskr
set FLASK_DEBUG=true
```

Criar o banco de dados:

```flask initdb```

Executar o app:

```flask run```
