# Chest-CT-Scan-Image-Classification-Project

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 



## Live matarials docs

[link](https://docs.google.com/document/d/1UFiHnyKRqgx8Lodsvdzu58LbVjdWHNf-uab2WmhE0A4/edit?usp=sharing)


## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```

## How to run?

```bash
conda create -n chest python=3.8 -y
```

```bash
conda activate chest
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```

### Mlflow dagshub connection uri

```bash
MLFLOW_TRACKING_URI=https://dagshub.com/Thisisstan36/mlflow-expirement-demo.mlflow \
MLFLOW_TRACKING_USERNAME=Thisisstan36 \
MLFLOW_TRACKING_PASSWORD=1f48976f300e2980abe9cf0273c750bdd4b1bb69 \
python script.py
```

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/Thisisstan36/mlflow-expirement-demo.mlflow

export MLFLOW_TRACKING_USERNAME=Thisisstan36 

export MLFLOW_TRACKING_PASSWORD=1f48976f300e2980abe9cf0273c750bdd4b1bb69
```