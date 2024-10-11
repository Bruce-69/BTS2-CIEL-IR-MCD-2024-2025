1) Quel est l'élément central du jeu League of Legends que nous cherchons à modéliser ?

Le champion

2) Comment pouvez-vous représenter l'identifiant unique d'un champion dans le modèle ?

On le représente avec une clée primaire (pk)

3)
Quels informations sont uniques à un champion ? Les informations non uniques seront alors des entités secondaires.

Les information uniques sont le nom, et les compétences

4)
comptétence = un seul champion
especes = plusieurs champions
roles = plusieurs champions
région = plusieurs champions
année de sortir = plusieurs champions
ressources = plusieurs champions



6) Outre les champions, quelles autres catégories d'informations sont importantes dans League of Legends et pourront être modélisées sous forme d'entités ?



5. Définition des attributs pour les entités secondaires
Pour chaque entité secondaire que vous avez identifiée, quelles informations sont nécessaires pour la décrire ?


7. Établissement des relations
Quelles sont les connexions logiques entre l'entité principale (champion) et les entités secondaires ?
Comment exprimeriez-vous ces connexions en termes de relations dans un MCD ?
8. Détermination des cardinalités
Pour chaque relation que vous avez identifiée, réfléchissez :
Un champion peut-il avoir plusieurs instances de cette caractéristique ?
Cette caractéristique peut-elle être partagée par plusieurs champions ?
Comment ces réponses se traduisent-elles en termes de cardinalités dans votre modèle ?
9. Création du diagramme
Utilisez draw.io pour créer votre diagramme. Quels symboles allez-vous utiliser pour représenter les différents éléments de votre MCD ?
Comment allez-vous organiser visuellement votre diagramme pour qu'il soit clair et facile à comprendre ?
Conseils
