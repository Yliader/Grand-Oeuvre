# Grand-Oeuvre
Général :
  Ces fichiers sont des documents de travail, la plupart sont aboutis mais présentent aussi des défauts liés surtout aux dimensions des composants et à leur perçage.
  
  L'archive se constitue de deux ou trois voir quatre documnts : 
- Un ou deux fichiers Kicad, souvent un pour les composants en façade et un pour le coeur (nommé core) du module. Les deux typons s'emboitent via des pins
- Un fichier pdf avec le schéma 
- Une potentielle BOM récapitulant les composants à souder SAUF LES POTs ET LES JACKS

Antimoine : 
- Module intéressant sur forme d'onde simple : carré triangle rampe et sinusoïde.
- noise pour des samples, beaucoup de crètes
- Sequenceur assez basique

Athanor : MODULE ABANDONNE, TROP INSTABLE
- ̶A̶t̶t̶e̶n̶t̶i̶o̶n̶ ̶a̶u̶ ̶r̶é̶g̶l̶a̶g̶e̶ ̶d̶e̶ ̶l̶a̶ ̶t̶e̶n̶s̶i̶o̶n̶ ̶v̶i̶a̶ ̶l̶e̶s̶ ̶t̶r̶i̶m̶m̶e̶r̶s̶ ̶!̶ ̶S̶i̶ ̶l̶e̶ ̶L̶M̶1̶3̶7̶0̶0̶ ̶c̶h̶a̶u̶f̶f̶e̶,̶ ̶b̶a̶i̶s̶s̶e̶r̶ ̶l̶e̶ ̶r̶a̶t̶i̶o̶ ̶d̶e̶ ̶t̶e̶n̶s̶i̶o̶n̶  Problème résolu dans le nouveau fichier
- R̶V̶2̶ ̶a̶ ̶e̶n̶l̶e̶v̶e̶r̶ ̶p̶o̶u̶r̶ ̶r̶e̶m̶p̶l̶a̶c̶e̶r̶ ̶p̶a̶r̶ ̶u̶n̶e̶ ̶r̶é̶s̶i̶s̶t̶a̶n̶c̶e̶ ̶d̶e̶ ̶p̶e̶t̶i̶t̶e̶ ̶v̶a̶l̶e̶u̶r̶ ̶o̶u̶ ̶u̶n̶ ̶t̶r̶i̶m̶m̶e̶r̶,̶ ̶e̶f̶f̶e̶t̶ ̶p̶e̶u̶ ̶p̶r̶o̶b̶a̶n̶t̶ ̶d̶e̶ ̶c̶e̶ ̶p̶o̶t̶e̶n̶t̶i̶o̶m̶è̶t̶r̶e̶ ̶s̶u̶r̶ ̶l̶a̶ ̶r̶é̶i̶n̶j̶e̶c̶t̶i̶o̶n̶ ̶e̶n̶ ̶H̶i̶-̶p̶a̶s̶s̶ ̶e̶t̶ ̶B̶a̶n̶d̶-̶p̶a̶s̶s̶ Résolu dans le nouveau fichier
- Attention toujours à l'intensité du signal de contrôle du cutoff à régler avec les trimers de 50k
- le potentiomètre RV2 a été remplacé par un trimer de 1K

Azoth : 
 - Concept abandonné car trop large pour peu d'intérêt en eurorack.
 - Montage complexe, ne se fier qu'au schéma en pdf
 
 Azoth V2 :
 - Module en réflexion
 
 Chaux :
 - Monté et testé 3 fois sans problème
 - modification possible : transformer le sommateur inverseur en non-inverseur.
 ̶ ̶ ̶R̶e̶v̶o̶i̶r̶ ̶l̶'̶i̶m̶p̶l̶a̶n̶t̶a̶t̶i̶o̶n̶ ̶d̶e̶s̶ ̶j̶a̶c̶k̶s̶ ̶q̶u̶i̶ ̶d̶é̶b̶o̶r̶d̶e̶ ̶u̶n̶ ̶p̶e̶u̶ ̶d̶e̶ ̶l̶a̶ ̶f̶a̶ç̶a̶d̶e̶  résolu avec les potentiomètres de befaco : https://shop.befaco.org/potentiometers/278-5x-potentiometer-100k.html
 
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
  ̶-̶ ̶B̶u̶g̶ ̶d̶e̶s̶ ̶s̶o̶r̶t̶i̶e̶s̶  Résolu sur le nouveau schéma : ajout d'AOP en tampon 
 
 Vapores :
 - Module en stase car peu d'intérêt, mais revoir les étages de sorties
 - Je conseil l'utilisation du schéma simplement, les fichiers kicad sont à revoir niveau implantation
 
 Vitriol : 
 - Bruyant dans l'alim mais pas dans les sorties audio des modules ?
 - Ratio des clocks assez réduit, voir pour plus de rapport cyclique.
 - Même problème avec les potentiomètres que Chaux (voir solution plus haut) 
 - Gros soucis de consomation --> structure des clocks abandonnées pour l'instant !
