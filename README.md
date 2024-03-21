```
mkdir dvc
cd dvc
code .
```

```
conda create -p venv python==3.8 -y
```

```
git init
```

```
touch .git ignore
```

```
touch README.md
```

```
touch requirements.txt
pip install -r requirements.txt
```

```
dvc repro
dvc dag
```