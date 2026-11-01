# Maison Facile — mises à jour

Ce dépôt ne contient que les **mises à jour** de Maison Facile :

- `versions.json` : la dernière version de chaque canal (`stable`, `test`), lue par les box ;
- l'onglet **Releases** : les archives `maison_facile.zip` de chaque version.

Adresse à utiliser dans la box (Appareils et services › Maison Facile › Configurer) :

```
https://raw.githubusercontent.com/akiserau3/maison-facile-releases/main/versions.json
```

Chaque archive est vérifiée par la box (empreinte SHA-256) avant installation, avec
sauvegarde et retour automatique à la version précédente en cas de problème.
