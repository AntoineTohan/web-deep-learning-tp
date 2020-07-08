# Projet deep learning

## Description

Interface web permettant la :

- Prédiction d'image de rongeurs
- Prédiction de musique : 

## Deployer l'app

Install repo and config env : 

```
git clone https://github.com/AntoineTohan/web-deep-learning-tp.git
pip install virtualenv

cd web-deep-learning-tp

virtualenv venv
virtualenv -p /usr/bin/python3.7 venv
source venv/bin/activate
pip install torch==1.1.0 torchvision==0.3.0
pip install -r requirements.txt
```

Start app :
```
python app/server.py serve
```