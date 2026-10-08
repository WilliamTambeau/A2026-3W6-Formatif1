# A24_S12_Lab1
Exercices : Trouvez les erreurs!

## Mission 1 :
La [connection SQL](Mission1/MissionsPossibles/appsettings.json) n'en est pas une valide - au moins pas sur les postes de travail

## Mission 2
Il manque un [DbSet explicite](Mission2/MissionsPossibles/Data/MissionDbContext.cs) pour acceder la propriétée de Produits, puis l'imolémentation de la requête LINQ dans le [Controlleur Produits](Mission2/MissionsPossibles/Controllers/ProduitsController.cs)

## Mission 3
Le nom de la [propriétée de connection dans le JSON](Mission3/MissionsPossibles/appsettings.json) ne "match" pas celle du Program.sc

## Mission 4
Le [controlleur/action Produits/Create](Mission4/MissionsPossibles/Controllers/ProduitsController.cs) ne cree pas une SelectList

## Mission 5
Le [View Upsert](Mission5/MissionsPossibles/Views/Categories/Upsert.cshtml) n'avais pas l'action do form correcte


J'ai passé beaucoups trops de temps ... je pensais que j'étais dans les views Categories, mais j'étais dans Produits