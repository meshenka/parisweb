# Ne passons pas à coté des choses simples

Présenté par Frank Taillandier [@DirtyF](https://twitter.com/DirtyF) et Bertrand Keller [@bertrandkeller](https://twitter.com/bertrandkeller)


[Slides](http://frank.taillandier.me/presentations/ne-passons-pas-a-cote-des-choses-simples/#0)

Une présentation autour de solution simple, sans BDD ou backend services pour la réalisation de site simple

On peut faire cela, assez facilement en s'appuyant sur quelques standard simples:
  * Markdown la wikisynthax
  * YAML synthaxe de fichier de configuration simple
  * JSON format léger de sérialisation

## Les avantages ?

  * léger
  * moins cher (que la mise en place d'un CMS)
  * ca tiens la charge
  * incassable
  * facile à livrer

## Qui utilise cela ?

  * mailchimp blog + user documentation
  * Facebook pour la doc de toutes leurs API
  * Google Design https://design.google.com/
  * Github, 
  * Mapbox
  * Netflix
  * getbootstrap
  * ...
  * Delicious Insight
  * cedexis
  * ICIJ

## Quels solutions ?

  * Contentfull https://www.contentful.com/
  * Forestry https://forestry.io/
  * __Hugo__ https://gohugo.io/
  * __Jekyll__ https://jekyllrb.com/
  * Middleman
  * Gatsby

## La puissance des API

On parle de __JAMStack__ : Javascript, APIs and Markup

Coupler avec des API JS ont peut aller très loin
  * jekyll + algolia : https://pixelastic.github.io/parisweb/ (sources ici : https://github.com/pixelastic/parisweb)
  * googlemaps
  *

## Workflows

Contraitement aux CMS _dynamiques_ les contenus sont versionné

On peut cabler un worflow sur __GIT__ :D :D :D

## Comment traiter les éléments dynamiques ?

  * Soumission de formulaire
  * Emails
  * etc..

Des solutions API existent!!! et si elles n'existent pas, développez les avec https://serverless.com/framework/docs/


## Conclusions

Une présentations intéressante sur l'évolution des technologies des générateurs, 
quelques découverte comme Forestry ou serverless.
