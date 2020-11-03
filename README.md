# Grand-Oeuvre
Général :
  Ces fichiers sont des documents de travail, la plupart sont aboutis mais présentent aussi des défauts liés surtout aux dimensions des composants et à leur perçage.
  
  L'archive se constitue de deux ou trois voir quatre documnts : 
- Un ou deux fichiers Kicad, souvent un pour les composants en façade et un pour le coeur (nommé core) du module. Les deux typons s'emboitent via des pins
- Un fichier pdf avec le schéma 
- Une potentielle BOM récapitulant les composants à souder SAUF LES POTs ET LES JACKS

Antimoine : 
- pas encore testé monté, testé sur platine de prototypage

Athanor : 
- Attention au réglage de la tension via les trimmers ! Si le LM13700 chauffe, baisser le ratio de tension.
- RV2 a enlever pour remplacer par une résistance de petite valeur ou un trimmer, effet peu probant de ce potentiomètre sur la réinjection en Hi-pass et Band-pass

Azoth : 
 - Concept abandonné car trop large pour peu d'intérêt en eurorack.
 - Montage complexe, ne se fier qu'au schéma en pdf
 
 Chaux :
 - Monté et testé 3 fois sans problème
 - modification possible : transformer le sommateur inverseur en non-inverseur.
 - Revoir l'implantation des jacks qui déborde un peu de la façade
 
 Creuset :
 - Bonne dynamique en module stéréo ou compression, mauvais en VCA simple 
 - Pas de réglage de la courbe (lin/exp) à ajouter ?
 
 Natron : 
 - Forte amplitude en modulation de fréquence
 - Un peu instable dans les racks bien fournis
 
 Noces :
 - Saturation selon les signaux
 - Fonctionne très bien sur les signaux de synthèses mais peu sur les samples.
 
 Paon :
 - Bug des sorties tampons FIXED
 
 Vapores :
 - Module en stase car peu d'intérêt, mais revoir les étages de sorties
 - Je conseil l'utilisation du schéma simplement, les fichiers kicad sont à revoir niveau implantation
 
 Vitriol : 
 - Bruyant dans l'alim mais pas dans les sorties audio des modules ?
 - Ratio des clocks assez réduit, voir pour plus de rapport cyclique.
 - Même problème avec les potentiomètres que Chaux
