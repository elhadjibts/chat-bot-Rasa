# Chatbot

Chatbot destiné à être integré au site de l'AIDE de l'Université d'Orléans pour répondre aux questions des étudiants.

## Pré-requis

- Python 3.6 / 3.7 / 3.8
- rasa < 3.0

## Démarrage

* rasa run -m models --enable-api --cors "*" --debug 
* rasa run actions
* ouvrir le fichier index.html

## Fabriqué avec

* [Rasa](https://rasa.com/) - Framework open source pour créer un chatbot
* [rasa-webchat](https://github.com/botfront/rasa-webchat) - Widget pour déployer un bot rasa sur n'importe quel site
* [PyCharm](https://www.jetbrains.com/fr-fr/pycharm/) - IDE pour Python

## Auteurs

* El hadji mbaye LO
* Gweltaz COLLET