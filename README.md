# RASA - Agents conv & bots

Le but ici est d'utilise [Rasa](https://rasa.com/docs/rasa/) pour créer un agent conversationnel qui permet de répondre à diverses questions par des réponses pré-enregistrées.

Pour chaque exercice, je vais créer une branche spécifique.

## Exercie 1
- Traduire en français l’exemple fournis avec l’installation de rasa
- Rajouter un intent pour la météo ainsi qu’une réponse associé

## Exercie 2
- Faire fonctionner un bot qui répond a des demandes de réservations d’hôtel ou a la commande d’un repas en ligne.
- Préparer le scénario
- Mettre en place le scénario

## Exercice Final
- avoir un bot qui permet de faire des réservations dans un restaurant
- pouvoir réserver, modifier et supprimer une réservation
- demander le menu du jour
- avoir la liste des allergènes

### Mise en place
- faire `rasa train` pour entrainer le model
- faire la commande `rasa run actions` pour lancer le serveur avec les actions
- faire `rasa shell` dans un autre terminal pour lancer le bot
- il est possible que certaines fois le bot n'arrive pas à sortir d'une story, il faut alors relancer le bot et faire le chemin souhaité
