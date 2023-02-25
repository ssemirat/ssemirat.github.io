---
title: "TasX"
layout: "default"
---
## TasX

*TasX* est un module d'extension de LaTeX utilisant l'extension *TeX4ht* pour générer non pas des PDF, mais des pages html.

*TasX* permet de rédiger des activités interactives (qcm, textes à trous,... avec données aléatoires et/ou figures interactives) pour publication en ligne, tout ça à partir d'une source *LaTeX*.

- Télécharger le dossier ci-dessous; ce dossier contient des exemples et les fichiers requis pour recompiler les exemples
- Pour voir des exemples d'activités crées : 
	- Ouvrir les fichiers `exemple###.html` avec votre navigateur (*Firefox* ou *Chrome* - fonctionne mal sous *Safari* ou *Edge*)
	- Recharger le fichier (CTRL+R sous *Firefox*) pour refaire l'activité avec d'autres valeurs
- Pour modifier les exemples : 
	- Editer par exemple le fichier `exempleA.tex`
	- Recompiler le fichier via la commande suivante (à noter : il est nécessaire d'avoir installé LaTeX et l'extension TeX4ht) :<br />
	 `htlatex exempleA.tex "tasx,mathml,charset=utf-8" " -cunihtf -utf8"`
- Il est possible d'intégrer les exercices dans une plateforme pédagogique (type moodle) avec enregistrement des scores des utilisateurs inscrits à la plateforme (les exercices communiquent avec la plateforme via la norme *SCORM*). 
	- Pour cela, par exemple l'outil *Reload project : Editor* peut être utilisé.<br />
	   Cet outil permet de créer à partir des fichiers d'exercices une arborescence de navigation, puis un unique fichier (un dossier compressé) contenant l'ensemble des exercices.
	- Une fois créé, le dossier compressé se téléverse dans la plateforme (par exemple, à travers l'outil *Paquetage SCORM* dans moodle).<br />

[Dossier à télécharger](https://cloud.univ-grenoble-alpes.fr/s/kjNk8ANostCXC9z)

[Aperçu](https://cloud.univ-grenoble-alpes.fr/s/kqaMGnLbTWcEJJX)
