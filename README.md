# Le pilotage de l'inclusion

## Démarrer le projet

1. `cd pilotage`
2. `source .venv/bin/activate`
3. `python manage.py runserver`

## Acces admin et DB

Pour l'accès à l'admin et pour récupérer la db (en sqlite3 pour l'instant), demander directement au patron

## ToDo

- [ ] Déplacer manage.py et les settings
- [ ] Créer le role pour les users aux droits limités dans l'admin
- [ ] Dockeriser la db postgres
- [ ] Passer la db en postgres (grace à la dockerisation)
- [ ] Réintégrer les `<iframe>` metabase directement dans le site, sans passer par le C1
- [ ] Créer une instance CC et héberger le site
- [ ] Créer le nécessaire pour un déploiement auto (via cmd Makefile ?)
