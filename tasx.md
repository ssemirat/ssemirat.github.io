---
title: "TasX"
layout: "default"
---
## TasX

[english version](#english-version)

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

## TasX {#english-version}

*TasX*  is a LaTeX extension package built on top of the *TeX4ht* extension to generate HTML pages instead of PDF documents.

*TasX*  makes it possible to create interactive activities (multiple-choice quizzes, fill-in-the-blank exercises, etc., with random data and/or interactive figures) for online publication, all from a *LaTeX*  source file.

- Download the folder below; it contains examples and all the files required to recompile them.
- To view the example activities:
  - Open the `example###.html` files in your web browser (*Firefox*  or *Chrome*  recommended — works poorly with *Safari* or *Edge*).
  - Reload the page (Ctrl+R in *Firefox*) to generate the activity again with different random values.
- To modify the examples:
  - Edit, for example, the `exampleA.tex` file.
  - Recompile the file using the following command (note: *LaTeX*  and the *TeX4ht*  extension must be installed):<br />
    `htlatex exampleA.tex "tasx,mathml,charset=utf-8" " -cunihtf -utf8"`
- The exercises can be integrated into a learning management system (such as Moodle), with users' scores automatically recorded. The exercises communicate with the platform through the *SCORM*  standard.
  - For this purpose, the *Reload Project: Editor* tool can be used, for example.<br />
    This tool creates a navigation structure from the exercise files and then packages all the exercises into a single compressed archive.
  - Once created, the compressed archive can be uploaded to the platform (for example, using the *SCORM Package* activity in Moodle).<br />

[Download the folder](https://cloud.univ-grenoble-alpes.fr/s/kjNk8ANostCXC9z)

[Preview](https://cloud.univ-grenoble-alpes.fr/s/kqaMGnLbTWcEJJX)
```
