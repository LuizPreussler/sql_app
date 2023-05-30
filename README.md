## Configuração do ambiente

Intalar as bibliotecas necessárias

```sh
pip install -r .\requirements.txt
```

se preferir, instalar as bibliotecas separadamente

```sh
pip install "fastapi[all]"

pip install SQLAlchemy
```

## Rodando a aplicação

Inicializando a API

```sh
python -m uvicorn sql_app.main:app --reload
```

> Opcional: Se for de interesse é possível navegar no banco de dados utilizando o [DB Browser](https://sqlitebrowser.org/)