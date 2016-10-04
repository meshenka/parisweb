# WebAssembly, la nouvelle cible de compilation pour le Web

Présenté par Benjamin Bouvieri (Mozilla) [@bnjbvr](https://twitter.com/bnjbvr)

WebAssembly est une cible de compilation qui vise à produire du code exécutable dans le navigateur, mais proche des directives bas niveau des processeurs
pour avoir une performance optimal

C'est le [ASM.js](http://asmjs.org/) du future

Petit nom: WASM (prononcé Wasèm)

C'est grace à ASM ou WASM qu'on peut faire tourner des jeu 3D dans le navigateur avec utilisation de
  * WebGL
  * WebAudio

Avec des perfs légerement moindre qu'en natif

La specification devrait etre implémenté d'ici début 2017 dans Firefox/SpiderMonkey (SpiderMonkey est la VM javascript de Firefox, comme v8 est celle de Chrome)

Avec WASM il deviendria possible de compiler de l'AS3 (flash), etc

La conf était assez technique, j'ai pas tout compris
