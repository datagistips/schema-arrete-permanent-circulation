# Changelog

## v0.4.1 (en cours)
- Regex SIRET

## v0.4.0 (corrections Etalab)
- Corrections apportées par Geoffrey Aldebert sur les regexes du schema.json
- Ajout d'un exemple valide dans resources
- Intégration continue OK
- Regex pour `ARR_INSEE`
- Format `uri` pour `ARR_URL`
- Regex multivalues sur le modèle de `(?:(?:^|,)^(Poids lourds|Véhicules utilitaires légers|Vélo-cargos|Tous véhicules))+$`
- Nouveaux usages pour `VEH_USAGE`
- Ajout de pattern pour `PERIODE_JH` : `(.*?)((\\d{1,2}:\\d{2})-(\\d{1,2}:\\d{2})|24/7)`
- `ID` Primary Key

## v0.3.3 (enrichissement des usages)
- Ajout de ressources (`sources`)
- Ajout de Julie Raffaillac dans les contributeurs
- Ajout de Vélo-cargos dans `VEH_TYPE`
- Ajout de valeurs dans `VEH_USAGE`

		- Citernes                                                                                                   
		- Véhicules d'approvisionnement des marchés                                                                                               
		- Véhicules effectuant du transport exceptionnel au sens de l'article R.433-1 du code de la route et munis d'une autorisation préfectorale
		- Véhicules de transport de matériaux
		- Véhicules porte-voitures
- Ajout de valeurs dans `VEH_CQA`
- Renommage de `SECTION_COTE` en `SECTION_SENS`
- Ajout de Nord, Sud, Est, Ouest dans `SECTION_SENS`

## v0.3.2
- Ajout de valeur `Autocars` dans `VEH_USAGE`
- Ajout de valeur `Transport de denrées animales ou végétales` dans `VEH_USAGE`

## v0.3.1
- Renommage de `SECTION_REGL_ID` renommé en `ID`
- Ajout de Véhicules de travaux dans `VEH_USAGE`
- Réordonnancement des champs `ARR_*`

## v0.3.0

Publication sur le repo github du Cerema en vue de [schema.data.gouv.fr](http://schema.data.gouv.fr/)

- Modification des types des champs `VEH_USAGE`, `VEH_MOTOR`, `VEH_CQA` de **array** vers **string** avec regex pattern 'Séparation par caractère `|`' car questionnement sur prise en charge du type **array** par la plateforme de publication et de validation des données d'Etalab
- Ajout de champ `SECTION_DEBUT_POINT`
- Ajout de champ `SECTION_DEBUT_REF`
- Ajout de champ `SECTION_FIN_POINT`
- Ajout de champ `SECTION_FIN_REF`

## v0.2.3

[Voir sur OpenDataFrance](https://opendatafrance.gitbook.io/fablog/territoires/chantiers/partage-des-donnees/standardisation/arretes-de-circulation#changelog)

## v0.2.2

[Voir sur OpenDataFrance](https://opendatafrance.gitbook.io/fablog/territoires/chantiers/partage-des-donnees/standardisation/arretes-de-circulation#changelog)

## v0.2.1

[Voir sur OpenDataFrance](https://opendatafrance.gitbook.io/fablog/territoires/chantiers/partage-des-donnees/standardisation/arretes-de-circulation#changelog)

## v0.2.0

Intégration du schéma sur le gitbook d'OpenDataFrance et revue par Jean-Marie Bourgogne

[Voir sur OpenDataFrance](https://opendatafrance.gitbook.io/fablog/territoires/chantiers/partage-des-donnees/standardisation/arretes-de-circulation#changelog)

## v0.1.0
[Première proposition du schéma sur framapad](https://lite.framacalc.org/9ms6-schema-circulation)
