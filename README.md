# Bac a sable

<br>

On se mettra d'accord pour savoir quand, mais ce repo servira a vous entrainer a manipuler git sur le terminal pour  
faire des sauvegardes et transferer des fichiers.  

Pour le contenu, on fera des exercices de base en utilisant du C et des concepts de base d'algorithmie,  
tout cela en utilisant uniquement le terminal, donc VIM au passage.

Vous aurez donc l'occasion de manipuler tout en meme temps, a plusieurs, donc poser des questions etc...  

<br>

---

<br>

Vous devrez d'abord clone le repo depuis votre terminal en utilisant : 

```bash
$ git clone https://github.com/sysmkr/sandbox.git
```
Ensuite rendez vous dans le repo en local en utilisan :

```bash
$ cd sandbox
```
Apres, creez votre branche propre branche que vous nomerez pareil que votre pseudo discord :

```bash
$ git checkout -b votre_psuedo_discord
```

Ensuite, allez sur le repo github via le navigateur et creer votre branche remote,  
Apres l'avoir fait, fetchez les modifications recentes : 

```bash
$ git fetch
```
Enfin, reliez votre branche locale et votre branche remote : 

```bash
$ git branch --set-upstream-to=origin/votre_pseudo_discord
```

Vous aurez maintenant une branche personnelle sur laquelle submit les exercices.
Pour ceux qui auront besoin je pourrai expliquer les autres commandes pour utiliser git.
