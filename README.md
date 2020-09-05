# BOIBOITES

Les boiboites sont un groupes de boites à ouverture automatique régies par un rasberry qui les ouvre en fonction de l'environnment humain (arrivées ou départ de personnes dans un périmètre fixe).

## Maitre

Le maitre est un raspberry qui communique avec les controleurs en wifi et/bluetooth (principale question du projet).

## Esclave

Etant donné le faible de contrôleurs asservis, on va partir sur des ESP32 avec wifi et bluetooth, ce qui permettra, respectivement, une gestion à travers un réseau (a priori inconnu) ou le bluetooth.

 
