# TEST SASS & TEST CROSS PLATFORM & TEST GITHUB PAGE SETTING

## SASS & CROSSPLATFORM

* Creation Projets Sass sur windows puis git init en local
* Pushing my local project on Clean repos from github
* Cloning my repos on my Linux system
* Test Modif et learn last sass syntaxe on linux
* and pushi it Linux local on github web repos
* Pull it in Windows system and watch if all works

## SYNTAXE SASS ENDING

* Imbrication des elements/selecteurs
    * Operateur & selection de l'element/selecteur précedent

* Variables $var:red;

* Mixins équivalent a des fonctions creation avec ous sans parametres

        Declaration:

            @mixin nomdumixin($parametre1,$parametre2,etc){
            background-color:$parametre1;
            width:$parametre2;
            height:$parametre2;
            }

        Utilisation:

            .article{
            @include nomudumixin(red,500px);
            }

* Import creations de plusieurs fichiers scss et permet de les import�s entre eux interessent pour structur�s et se rep�r� rapidements, il faut idealement mettre en place une hierarchi de structures afin de rendre ceci beaucoup plus simple aussi bien a mettre en place que de se reperer

        Syntaxe : @import "cheminfichier.scss";


* Extends (Heritage) Affilier des propri�t� d'une classe a une autre classe


	    Syntaxe :  .classe1{ color = red;
			                 background-color:blue;}

		           .classe2{ @extend .classe1;} // Heritage des propriete de Classe1


## GITPAGE SETTING

* On choisi un theme dans les settings
* Creer un fichier _config.yml dans le repos pour configration du theme de gitpage
* Visiblement sa creer un lien (website) du fichier html contenu dans repos permet de voir en direct du contenu du repos
* On peut desactiver aprés l'avoir activé en mettant none a la place de master and save dans les setting de gitpage.
    * Néanmoins le fichier de configuration _config.yml reste present dans le dépots donc penser a supprimer si clearing

https://pages.github.com/
