# Thème 3 : Les Structures de données
## Vidéo 

<iframe width="560" height="315" src="https://www.youtube.com/embed/IJJgcZ2DEs0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Vocabulaire

### Identifier un objet 

1. Je souhaite un film s'appelant "la Guerre des Boutons" 

    a. Pourquoi cette information est insuffisante pour identifier le film ?
    
    b. Quelle information dois-je ajouter pour trouver mon film ?
    
 2. Je cherche un livre s'appelant Raisonnements divins, de Martin Aigner et Günter M. Ziegler.

     a. Pourquoi cette information n'est-elle pas suffisante pour identifier ce livre ?
     
     b. Quelle information devrais-je ajouter à ma recherche pour préciser de quel livre il s'agit ?
    
### Etudier des données d'un livre 
 
Dans cette partie, on étudie les données du livre Histoires et cultures du libre, de Camille Paloque-Bergès et Christophe Masutti. Sur sa notice sur le site de la BNF, on lit les informations suivantes.

* Type(s) de contenu et mode(s) de consultation : Texte noté : sans médiation
* Titre(s) : Histoires et cultures du libre [Texte imprimé] : des logiciels partagés aux licences échangées / sous la direction de Camille Paloque-Berges, Christophe Masutti
* Publication : [Paris] : Framasoft : Inno cube ; [Rocquencourt] : INRIA, DL 2013
* Impression : impr. aux États-Unis
* Description matérielle : 1 vol. (XXIII-556 p.) : ill., couv. ill. ; 21 cm
* Collection : Framabook ; 13
* Note(s) : Notes bibliogr.
* Autre(s) auteur(s) : 
        -   Paloque-Bergès, Camille - Directeur de publication 
        -   Masutti, Christophe (1975-....). Directeur de publication
 * Sujet(s) :
        -   Logiciels libres -- Histoire
        - Logiciels libres -- Aspect économique -- Histoire
* Indice(s) Dewey : 005.3 (23e éd.)
* Numéros :
ISBN 978-2-9539187-9-3 (br.) : 25 EUR
EAN 9782953918793
 * Notice n° : FRBNF43580627 <br>

**Questions**

1. Quelles sont les données permettant d'identifier précisement le livre ?
2. Quelles données sont plutôt destinées à des personnes ? Quelles données sont plutôt destinées à des ordinateurs ? 
3. Quelles sont les types de données ? Donner la nature et un exemple. 


### Bilan 

Recopier dans Word la syntèse suivante : 

* Une **collection** est un ensemble d'objets (concrets ou abstraits) dont on collecte des données, partageant les mêmes descripteurs.
* Un **objet** est un élément de cette collection.
* Un **descripteur** désigne l'aspect de l'objet concerné par la donnée.
* Une **valeur** est l'information elle-même.
* Le **type d'une valeur** est la nature de cette information.

De plus, si une donnée concerne une personne, on dit que c'est une **donnée personnelle**. 

### Applications 
1. On considère le sac que vous emenez avec vous au lycée. La collection auquel il appartient est donc l'ensemble des articles vendus par le magasin où vous l'avez acheté. Donner quelques descripteurs pouvant s'appliquer à ce sac à dos, ainsi que les valeurs correspondantes.

2. On considère les données vous concernant, dans la base de donnée d'Ecole Directe.
Donner quelques descripteurs pouvant vous concerner, ainsi que les valeurs correspondantes.

## Données et tableur

1.Créer un document Word - Enregristrer le dans votre OneDrive/SNT en le nommant SD-Tableur-NOM-Prénon

2. Sur internet, aller sur [data.gouv.fr](https://www.data.gouv.fr/fr/)

3. Rechercherz *Films entres* dans le champ de recherche.

4. Téléchargez et ouvrir le fichier *Films ayant réalisé plus d'un million d'entrées* au format .xlsx.

5. Noter vos réponses dans Word:
    
    a.  Quel est le film ayant fait le plus d'entrées en 2021 ?
    
    b. Quel est le film français ayant fait le plus d'entrées en 2018 ?
    
    c. Quelle est la nationalité du film ayant fait le plus d'entrées en 2010 ? 

6. Dans l'onglet *2021*, sélectionner la ligne 7, aller dans le menu *Données* et cliquer sur *Filtre*. 
    
    a. Filtrer par nationalité, décocher tout sauf *FR* puis valider. 
    
    b. Quels sont les trois films français ayant fait le plus d'entrée en 2021 ?

7.  On souhaite connaître le nombre de films français de cette liste. 

8.  Dans la cellule B33, écrivez =SOUS.TOTAL(3;B8:B32) (cette fonction permet de calculer le nombre de cellules de la colonne E, mais seulement pour les cellules filtrés). La cellule devrait afficher 7, soit 7 films dans cette liste.

9. On souhaite connaître le nombre d'entrée réalisées par les films français de cette liste. Dans la cellule E33, écrivez =SOUS.TOTAL(9;E8:E32) (cette fonction permet de calculer la somme de la colonne E, mais seulement pour les films filtrés). La cellule devrait afficher 12,40, soit 12,40 millions d'entrées.

10. Supprimez le filtre sur la nationalité (vous devez à nouveau voir toutes les nationalités), puis triez la colonne sortie par date.  Les trois premiers films affichés devraient être Adieu les Cons, Conjuring 3: The Devil Made Me Do It, Cruella.

11. Le premier de ces films est sorti en 2020. Pourquoi est-il affiché dans cette liste qui concerne l'année 2021 ?

12. On veut connaître, parmi les films des États-Unis sortis en 2021, quels sont les trois films ayant réalisé le plus d'entrée.
Décrire sur votre compte-rendu votre démarche pour répondre à cette question : Quels filtres appliqués ? Quels tris ?
Répondre à la question.

13. Exporter votre fichier Word en pdf et envoyer dans Devoir > 2GTx-Tableur

## format .csv

1. Creer un document Word, enregristrer-le dans votre dossier OneDrive/SNT sous le nom csv-python-NOM-prenom
2. Que signifie les initiales du format csv, donner la signification en anglais et une traduction en français. 
3. Telecharger le document [Informaticiens](./SD/informaticiens.csv) et enregristrer-le dans votre OneDrive. 
4. Quel est le descripteur de ce fichier ? 
5. Quel est le symbole utilisé comme séparateur ? 
6. En quelle année est né Ada Lovelace ? 
7. Quel est le prénom de Mme Hamilton ?
8. Qui, parmi les personnes listées dans le fichier, est né plus tard ? 

## csv et python
1. Aller sur [cette page](https://www.insee.fr/fr/statistiques/2540004?sommaire=4767262)
2. Telecharger le *Fichiers par départements de naissance* au format csv 
3. Le decompresser et placer le fichier dpt2021.csv dans votre Ipad, dans votre dossier Carnet (pas dans OneDrive et ne surtout pas l'ouvrir)
4. Ouvrir un fichier Carnets (dans le meme dossier que dpt2021, les 2 fichiers doivent communiquer). 
5. Taper les lignes suivantes

import pandas<br>
prenoms = pandas.read_csv("dpt2021.csv", sep=";")<br>
print(prenoms)<br>

6. Executer le programme : 
 
 - Si vous voyez afficher un tableau, le programme s'est exécuté sans erreur : passez à la question suivante.

 - Si une erreur apparaît, essayez de la comprendre et de la corriger. Vérifier que le programme carnet et dpt2021.csv sont dans le mêmme répertoire.

**Explication du tableau** 
La première ligne correspond aux descripteurs du fichier :

**sexe** : sexe du prénom (1 pour un garçon ; 2 pour une fille) ;

**preusuel** : prénom ;

**annais** : année de naissance (attention : il s'agit de l'année de naissance, et non pas du prénom Anaïs) ;

**dpt** : département de naissance ;

**nombre** : nombre d'enfants portant ce prénom.

Certaines valeurs (pour les années et les départements) sont égales à XXXX. Cela correspond sans doute à des données incorrectes ou inconnues.

Chaque ligne suivante correspond à une données différente. Par exemple, l'antépénultième ligne (avant-avant dernière ligne, numéro 3676679) signifie : *En 2013, dans le département de Seine-Saint-Denis (93), trois filles sont nées avec le prénom Zyna.*

7. Complétez la phrase suivante avec les données d'une des lignes que vous voyez affichées *En ????, dans le département ???? (??), ??? ????? sont nés/nées avec le prénom ????.*

Il est possible d'afficher une cellule du tableau en particulier. Par exemple, le programme suivant donne l'année de naissance de la ligne numéro 3784668.

import pandas<br>
prenoms = pandas.read_csv("dpt2021.csv", sep=";")<br>
recherche = prenoms.loc[3784668, "annais"]<br>
print(recherche)<br>


8. Exécutez-ce programme et vérifiez qu'il donne la valeur attendue.

9. Modifiez le programme précédent pour qu'il affiche uniquement un des prénoms du tableau. Recopiez sur votre compte-rendu la ligne de votre programme `recherche = prenoms.loc[???????].

10. Il est aussi possible d'afficher toute une ligne ou toute une colonne, en utilisant la syntaxe prenoms.loc[3676679, :] (pour avoir toute la ligne numéro 3676679), ou prenoms.loc[:, "annais"] (pour avoir toute la colonne annais (année de naissance)).

Modifiez votre programme pour qu'il affiche la colonne des prénoms. Recopiez l'ensemble de votre programme sur le compte-rendu.

### Recherche dans la base de données. 

1.Recopier le programme suivant dans Thonny, et exécutez-le.

import pandas<br>
prenoms = pandas.read_csv("dpt2021.csv", sep=";")<br>
recherche = prenoms.loc[(prenoms['dpt'] == "38"), :]<br>
print(recherche)<br>

Vérifiez que ne sont affichés que les prénoms donnés dans le département de l'Isère (38).

2. Dans le programme précédent, remplacez la troisième ligne (recherche = prenoms.loc…) par :
recherche = prenoms.loc[(prenoms['annais'] == "2021"), :]

Exécutez le programme, et vérifiez que ne sont affichés que les prénoms donnés l'année 2021.

3. Il est possible de combiner les conditions. Remplacez encore la troisième ligne (recherche = …) par :

recherche = prenoms.loc[(prenoms['dpt'] == "38") & (prenoms['annais'] == "2021"), :]

Exécutez-le, et vérifiez que ne sont affichés que les prénoms donnés en Isère (38), l'année 2021 (remarquez le symbole & situé entre les deux conditions).

4. Il est possible aussi de trier les résultats. Ajoutons cela à la dernère recherche :

import pandas<br>
prenoms = pandas.read_csv("dpt2021.csv", sep=";")<br>
recherche = prenoms.loc[(prenoms['dpt'] == "38") & (prenoms['annais'] == "2019"), :]<br>
tri = recherche.sort_values(by="nombre")<br>
print(tri)

Dans cet exemple, les résultats sont triés par le nombre d'enfants portant ces prénoms.

Dans le cas de recherches plus complexes, on peut découper le travail en faisant des recherches successives : 
la ligne recherche = prenoms.loc[(prenoms['dpt'] == "38") & (prenoms['annais'] == "2019"), :]<br>
peut être remplacée par 
recherche = prenoms.loc[(prenoms['dpt'] == "38") :]<br>
recherche = recherche.loc[(prenoms['annais'] == "2019"):]<br>

etc.


5. Répondre à cette question en lisant le résultat du programme de la question précédente. Ignorer les prénoms rares.

    a. En 2019, en Isère, quel a été le prénom le plus donné ?

    b. En 2019, en Isère, quel a été le prénom de filles le plus donné ?

    c.  En 2019, en Isère, combien de garçons ont été prénommés Gabriel ?

6. Répondre à cette question en modifiant le programme qui est actuellement ouvert dans Thonny.

    a. En quelle année êtes-vous né·e ? Dans quel département ?

    b. Durant votre année de naissance, dans votre département, quels ont été les prénoms les plus donnés aux filles et aux garçons ?

    c. Durant votre année de naissance, dans votre département, combien d'enfants ont été nommés avec le même prénom que vous ?


