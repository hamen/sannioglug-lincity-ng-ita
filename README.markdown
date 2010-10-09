#SannioGLUG 2010

# Traduzione italiana di Lincity-NG
http://lincity-ng.berlios.de/wiki/index.php/Main_Page

## Installazione su Ubuntu
Copiate il repository: 

     git clone git://github.com/hamen/sannioglug-lincity-ng-ita.git
A questo punto dovrete creare dei link simbolici nella cartella

    /usr/share/games/lincity-ng/

Nella cartella

    /usr/share/games/lincity-ng/locale/
dovrete creare un link _it.po_ al file _it.po_ che avete nel repository.

Nella cartella

    /usr/share/games/lincity-ng/locale/gui/
dovrete creare un link _it.po_ al file _it.po_ che avete nel repository


Nella cartella

    /usr/share/games/lincity-ng/help/
dovrete creare un link _it_ alla cartella _it_ che avete nel repository

In questo modo potrete cominciare a giocare in italiano anche con una traduzione parziale.

## Aggiornare i file della traduzione
Per mantenere aggiornati i vostri file in italiano e godere delle ultime traduzioni, vi basterà aggiornare il repository git:

    git pull origin master

_SannioGLUG 2010_
