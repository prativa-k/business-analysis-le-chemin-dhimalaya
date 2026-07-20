# 13 – Solution proposée

## Objectif

Présenter la solution retenue pour répondre aux besoins identifiés dans le cahier des charges.

---

# Présentation de la solution

La solution proposée consiste à développer un nouveau site internet pour le restaurant **Le Chemin d'Himalaya**.

Le site permettra :

- de présenter le restaurant ;
- de consulter le menu ;
- de réserver une table ;
- de contacter le restaurant ;
- de créer un compte utilisateur ;
- de déposer des avis et des commentaires ;
- de gérer le contenu du site depuis un espace d'administration sécurisé.

---

# Architecture retenue

Le projet repose sur une architecture **Client / Serveur**.

L'application est organisée selon le modèle **MVC (Modèle – Vue – Contrôleur)** afin de séparer :

- les données (Modèle) ;
- les traitements (Contrôleur) ;
- l'interface utilisateur (Vue).

Cette architecture facilite l'organisation du projet et la séparation des responsabilités.

---

# Environnement de développement

Le développement est réalisé avec :

- Visual Studio Code ;
- Docker ;
- DevContainer.

L'application est exécutée sur les serveurs locaux définis dans le cahier des charges.

---

# Résultat attendu

La solution permettra de remplacer le site existant par un site répondant aux besoins fonctionnels définis dans le cahier des charges tout en proposant :

- un espace public destiné aux visiteurs ;
- un espace client ;
- un espace administrateur sécurisé.
