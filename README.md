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
dvc init
dvc repro
dvc dag
```
```
dvc add <file name>
git add <file name> && git commit -m "file added"

dvc remote add myremote <any_remote_location>

dvc push
```

DVC Official Documentation Link: [Click Here!](https://dvc.org/doc)
