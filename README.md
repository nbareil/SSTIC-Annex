# À propos de SSTIC-Annex

Ce repository tente de regrouper le maximum de liens vers tout ce qui
est disponible sur sstic.org en utilisant [git-annex](http://git-annex.branchable.com/) :

 - Les articles
 - Les slides
 - Les vidéos

# Avantages

Ce repository est une sorte de *meta-repository*, en gros, ce n'est
qu'une liste de liens HTTP vers sstic.org.

Vous pouvez ainsi naviguer dans l'arborescence et choisir ainsi les
fichiers que vous souhaitez télécharger à l'aide de `git-annex`. C'est
ainsi très pratique pour un ordinateur portable, car la loi de Murphy
étant toujours vérifiée, vous n'avez jamais la connectivité au bon
moment.

# Comment l'utiliser ?

Par exemple, pour récupérer une présentation  :

```
$ git clone https://github.com/nbareil/SSTIC-Annex.git
$ cd SSTIC-Annex
$ git annex get SSTIC_2004/Rump_sessions/SSTIC04_rump_Biondi_scapy.pdf
get SSTIC_2004/Rump_sessions/SSTIC04_rump_Biondi_scapy.pdf (from web...)
...
ok
(Recording state in git...)
$ evince SSTIC_2004/Rump_sessions/SSTIC04_rump_Biondi_scapy.pdf
```

Vous pouvez aussi télécharger tout d'un coup :


```
$ git annex get SSTIC_2004/Rump_sessions/

```

Soyez raisonnable :)
