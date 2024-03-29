# iascan

`iascan` est un outil de balayage d'adresses IP qui intègre des services tels que Shodan et InternetDB pour fournir des analyses approfondies et des informations de sécurité. Il est conçu pour être simple et efficace, permettant aux utilisateurs de scanner rapidement des adresses IP uniques ou des plages d'adresses IP.

## Installation

Pour installer `iascan`, exécutez simplement la commande suivante :

    pip install iascan

Assurez-vous d'avoir `pip` installé et de l'utiliser avec une version de Python supérieure à 3.6.

## Utilisation

Pour scanner une adresse IP spécifique en utilisant Shodan et InternetDB, utilisez la commande suivante :

    iascan -ip 203.0.113.5

Pour scanner une liste d'adresses IP à partir d'un fichier, utilisez :

    iascan -list ip_list.txt

Le fichier `ip_list.txt` doit contenir une adresse IP par ligne.

## Fonctionnalités

- Recherche d'adresses IP uniques en intégrant des données de Shodan et InternetDB.
- Balayage d'une liste d'adresses IP avec des informations enrichies.
- Affichage des informations détaillées telles que les hostnames, les ports ouverts, les tags associés, les vulnérabilités connues, et d'autres métadonnées.
- Utilisation simple en ligne de commande.

## Contribution

Les contributions à `iascan` sont les bienvenues ! Si vous avez des suggestions ou des améliorations, n'hésitez pas à ouvrir une issue ou une pull request sur notre dépôt GitHub à l'adresse suivante : [GitHub - iascan](https://github.com/yourusername/iascan).

## Licence

`iascan` est distribué sous la licence MIT. Voir le fichier `LICENSE` pour plus d'informations.
