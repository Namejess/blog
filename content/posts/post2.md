---
title: "Suckless, minimalisme logiciel et simplicité"
date: 2023-01-26T09:52:15+01:00
draft: false
---

Depuis les débuts du mouvement du logiciel libre, il existe un sous-mouvement qui se concentre sur l'efficacité et la simplicité du code. Ce mouvement s'appelle [**Suckless**](https://suckless.org/) et il a pour objectif de produire des logiciels simples, légers et élégants.

Simples, dans la conception, pas nécessairement dans l'utilisation. Un de leur projet phare, [**dwm**](https://dwm.suckless.org/), nécessite de customiser son installation et ses fichiers de configuration puis de recompiler le programme.

Légers, car ils sont conçus pour être rapides et consommer peu de ressources. Ils sont souvent écrits en C, ce qui permet de les compiler pour une cible spécifique et de les optimiser pour cette cible.

Élégants, Ils sont souvent conçus pour être utilisés avec un clavier et un terminal, ce qui permet de les utiliser de manière efficace et rapide.

---

J'ai rencontré beaucoup de personnes qui ont influencé ma façon de voir l'informatique, le logiciel. Une vision qui s'entrechoque avec des valeurs personnelles (que ce soit écologique, philosophique, politique). Car prendre le temps de bricoler un auto-hébergement, de debugguer des installations/mise à jour de logiciels libres un dimanche aprem ou encore de se renseigner sur comment gagner en performance sur des anciennes machines afin de pouvoir les réutiliser en dit assez long sur notre façon de consommer, de voir le monde.

Le minimalisme est au cœur de la philosophie de Suckless. Les développeurs cherchent à éliminer tout ce qui est inutile dans le code, en se concentrant uniquement sur les fonctionnalités qui sont absolument nécessaires. Cela signifie que les logiciels Suckless sont souvent très rapides et consomment peu de ressources système.

Etant dans une formation de concepteur développeur web, je me suis intéressé à la philosophie de Suckless. Le [**manifeste**](https://suckless.org/philosophy/) et les arguments qui sont développés résonnent en moi. [**Web Sucks**](https://suckless.org/sucks/web/) est un article qui résume particulièrement bien les...dérives du web. De simples pages censées être des articles de blog sont devenues des applications web, avec des frameworks, des librairies, des outils de build, des outils de tests, des outils de déploiement, engendrant des coûts énergétiques, humains et financiers. Et pourtant, ces outils ne sont pas toujours nécessaires. Il est possible de faire des choses simples avec des outils simples.

[**KISS**](https://en.wikipedia.org/wiki/KISS_principle) bon sang.

---

L'un des avantages les plus importants des logiciels Suckless est leur simplicité. Contrairement à de nombreux logiciels modernes, les logiciels Suckless ne sont pas encombrés d'options et de fonctionnalités inutiles.

Tout ça pour dire que mon apprentissage de [**Rust**](https://www.rust-lang.org/fr) va dans ce sens. Je vais essayer de faire des choses simples, avec des outils simples. Et si je dois utiliser des outils plus complexes, je vais essayer de comprendre comment ils fonctionnent et de les utiliser de manière simple.

Pour le plaisir, voici la différence de nombre de lignes de code entre i3 et dwm :

<img src="https://cdn.discordapp.com/attachments/1161206521972138007/1166376617514377256/image.png?ex=656f2ddf&is=655cb8df&hm=e9b884c19282584bde80331354b026315da8c6d16e2d2954c74a0c260bd6d6f8&"  />

<img src="https://cdn.discordapp.com/attachments/1161206521972138007/1166376771931877466/image.png?ex=656f2e04&is=655cb904&hm=b5e1de6e44305526c125e2a38761391697f6fca05c0240e1455ad6782ad67dea&"  />

On est sympa et on garde que le C chez i3, pour un total de 26000 lignes de code.

Chez dwm, c'est 2500.

Je ne sais pas vous, mais moi, ça me fait réfléchir.
En plus de me faire peur.