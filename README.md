# docker-jupyterlab

### Jupiterlab env with Python, Julia, R


Przygotowanie projketu
```bash
python3 -m cookiecutter https://github.com/sebkaz/jupyterlab-project --no-input --config-file=jupyterlab_template.yml --overwrite-if-exists
```

Uruchomienie

```bash
cd jupyterlab
docker-compose up -d --build
```

Zamknięcie: 

```bash
docker compose down
```