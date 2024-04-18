|_Doc. #_|_Rédacteur_|_Création_|_Mise à jour_|_Version_|
|:---:|:---:|---:|:---|
|___0022___|_Loïc Drouet_|_Mardi 22 novembre 2022_|_Jeudi 18 avril 2024_|___1.0.3___|

# Modèle de nommage de dumps par phpMyAdmin

## Modèle de nommage d'un dump de DATABASE par phpMyAdmin

Pour l'export d'une base de données, copier le code suivant :

```sql    
%Y_%m_%d_%H%M%S_@DATABASE@_@SERVER@
```

## Modèle de nommage d'un dump de TABLE par phpMyAdmin

Pour l'export d'une table de la base de données, copier le code suivant :

```sql    
%Y_%m_%d_%H%M%S_@TABLE@_@DATABASE@_@SERVER@
```

