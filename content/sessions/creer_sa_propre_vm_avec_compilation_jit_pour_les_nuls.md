---
key: creer_sa_propre_vm_avec_compilation_jit_pour_les_nuls
title: "Créer sa propre VM avec compilation JIT pour les nuls"
speakers:
  - olivier_poncet
type: canadienne
day: 1
time: 10h15
duration: 45 minutes
room: petite_salle
---

La compilation « Just In Time » est une technique d'exécution très utilisée depuis de nombreuses années au sein des machines virtuelles de langages tels que Java, C#, JavaScript, etc .... Elle permet d'interpréter et d'exécuter un byte-code tout en le transformant « à la volée » vers le langage machine natif de la machine hôte nous permettant ainsi d'obtenir des performances bien plus élevées lors d'une seconde exécution du code.

Ces techniques de recompilation dynamique peuvent être complexes à appréhender lorsque l'on est néophyte sur le sujet, c'est pourquoi nous allons démystifier ensemble ce sujet

Dans ce talk nous mettrons en œuvre et en live notre propre machine virtuelle avec JIT intégrée pour une calculatrice [RPN](https://en.wikipedia.org/wiki/Reverse_Polish_notation) (Reverse Polish Notation), sans aucun framework ni infrastructure de compilation extérieure, en émettant nous même le code machine `x86_64` nécessaire à l'exécution.

Puisse le dieu des « segmentation fault (core dumped) » être avec nous !