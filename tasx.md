---
title: "TasX"
layout: "default"
---
## TasX

*TasX* est un module d'extension de LaTeX que j'ai développé.

Il permet de rédiger des activités interactives (qcm, textes à trous,... avec données aléatoires et/ou figures interactives) pour publication en ligne, tout ça à partir d'une source *LaTeX*.

- Télécharger le dossier "exemples" ci-dessous; ce dossier contient les fichiers requis pour recompiler les exemples
-- Pour voir des exemples d'activités crées : 
-- Ouvrir les fichiers exempleA.html et exempleB.html avec votre navigateur
-- Recharger le fichier (CTRL+R sous Firefox) pour refaire l'activité avec d'autres valeurs
- Pour modifier les exemples d'activités : 
-- éditer par exemple le fichier exempleA.tex 
-- recompiler le fichier via la commande (à noter : il est nécessaire d'avoir installé LaTeX et l'extension Tex4ht) :
<p style="align:center;font-family:system-ui;">htlatex exempleA.tex "tasx,mathml,charset=utf-8" " -cunihtf -utf8"</p>
- Il est possible d'intégrer les exercices dans une plateforme pédagogique (type moodle) avec enregistrement des scores des utilisateurs inscrits à la plateforme. 
-- Pour cela, j'utilise l'outil Reload project : Editor : cet outil permet de créer à partir des fichiers d'exercices une arborescence de navigation, puis un unique fichier (un dossier compressé) contenant l'ensemble des exercices
-- Une fois créé, le dossier compressé se téléverse dans la plateforme (par exemple, à travers l'outil Paquetage SCORM dans moodle).

<iframe src="https://drive.google.com/embeddedfolderview?id=1cPlp4t8IRXIjJ2aRi-W4OXJ90bkmoat6" width="100%" height="100%"></iframe>

