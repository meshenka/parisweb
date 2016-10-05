# Éco-conception : mon site web au régime

Présenté par Frédéric Bordage (GreenIT) [@greenit](https://twitter.com/greenit)

[Slides](https://www.greenit.fr/wp-content/uploads/2016/10/2016-09-ParisWeb-v0.6-light.pdf)

Une présentation assez intéressante bien que très formel et sans véritable retour d'expérience sur
l'éco-conception

Le constat
  * Le nombre de site à fait x71 en 10 ans
  * le poids d'une page web à fait x3 en 5 ans

Le Web polue, et fortement
  * 60% conception fonctionnelle / conception technqiue
  * 15% Développement
  * 25% Hébergement

25% de la polution viens de l'hébergement (seulement)
60% provient de la conception fonctionnelle et techniques (taille des pages, des images, fonctionnalité coutant beaucoup de CPU)

En effet c'est dans les phases de conceptions que les décisions couteuses vont se faire
  * Design lourd
  * Animations
  * Poids des pages
  * Cout en bande passante
  * Equipements nécessaires pour supporter la charge
  * Technologies employés

Une grosse partie de cette polution provient des Terminaux: Soyons léger, soyons device-friendly, soyons batterie-friendly

|          | Terminaux | Réseau | Data Center |
|----------|-----------|--------|-------------|
| Energie  |    X      |        |             |
| GES      |    X      |        |             |
| Ressources |   X     |        |             |
| Dechets  |    X      |        |             |
| Eau      |           |  X     |     X       |


Quelques conseils pour améliorer le bilan carbone de vos sites

  * Supprimer les fonctionalités secondaires
  * Mobile First
  * UI light et simple
  * Compresser les images, css, js
  * Limiter les animations JS
  * Ne pas faire de Preload
  * Utiliser est appels AJAX plutot que des reloads complets
  * Préférer les pages statiques (ou un cache fort)

__SIMPLE IS BEAUTYFULL__


Il y a une petite communauté française active, leader dans le monde [GreenIT](http://greenit.fr)
Cette communauté met à dispositions quelques outils:
  * Une liste de 115 recommandations http://checklists.opquast.com/ecoconception-web/

Bonne conférence pour une première approche des concepts de l'éco-conception et pour briser quelques idées préconçus
J'ai cependant trouvé un vrai manque d'un retour d'expérience opérationnel sur le Sujet en dehors de quelques exemples triviaux.


