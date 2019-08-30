# E-réputation

> Le projet E-réputation développé par <a href="https://www.facebook.com/jdioui.mohammed">Jdioui Mohamed</a>, <a href="https://www.facebook.com/myriam.tazlaoui">Tazlaoui Myriam</a>, <a href="https://www.facebook.com/Puthus09">Soulayman Soubai</a>, <a href="https://www.facebook.com/profile.php?id=100001647804492">Zebri Younes</a>, <a href="https://www.facebook.com/lami.saidi">Saidi Lamiya</a>, <a href="https://www.facebook.com/kantame.kanssouguiba">Kantame Kanssouguiba</a> stagiaires à EBF et Élèves-Ingénieurs.


## Mise en situation

La mission consiste à mettre en place une solution informatique qui permet d'obtenir des articles négatifs qui touchent à la réputation de la région Marrakech-Safi. Ces articles sont envoyés à <a href="https://www.cnt.ma"> la confédération nationale de tourisme </a> afin de prendre soin de l'image de la région. Parmis les avantages de la E-réputation:
  - Tout savoir sur ce qui se dit.</li>
  <li>Anticiper les bad buzz.</li>

## Choix Techniques

Parmis les technologies qu'on a travaillé avec:

- <a href="https://www.google.co.ma/alerts">Google Alerts ou Google Alertes</a> est un service qui envoie un e-mail ou une alerte lorsqu'une nouvelle page web correspondant aux mots-clés que l'on a choisi, apparaît dans les résultats Google.
<li><a href="https://www.python.org/">Python </a> est un langage de programmation interprété, multi-paradigme et multiplateformes. Il favorise la programmation impérative structurée, fonctionnelle et orientée objet.</li>
<li><a href="https://www.mongodb.com/fr">Mongodb </a> est un système de gestion de base de données orienté documents, répartissable sur un nombre quelconque d'ordinateurs et ne nécessitant pas de schéma prédéfini des données.</li>
<li><a href="https://laravel.com/">Laravel </a> est un framework web open-source écrit en PHP respectant le principe modèle-vue-contrôleur et entièrement développé en programmation orientée objet. Laravel est distribué sous licence MIT, avec ses sources hébergées sur GitHub.</li>
<li><a href="https://www.chartjs.org/">Chartjs </a> est une bibliothèque de code JavaScript open source simple mais flexible pour les concepteurs et les développeurs.</li>

## Setup instructions

- <code>pip install beautifulsoup4</code>
- <code>pip install lxml</code>
- <code>pip install requests</code>
- <code>from bs4 import BeautifulSoup as bs</code>
- <code>pip install feedparser</code>
- <code>pip install pymongo</code>
- <code>composer global require "laravel/installer=~1.1"</code>
- <code>npm install chart.js --save</code>

> Configuration de Laravel pour utiliser MongoDB comme une base de donnée (la même base de donnée utilisé lors du webscrapping pour assurer une cohérence)
<a href="https://github.com/jenssegers/laravel-mongodb?fbclid=IwAR2fQJ2CvvSX7ioR9UBi2SNK1tkzaJZgz3DCtC8ETdA9RHTPbGnhJi2d3cw">Site Web</a>

> exécution automatique du code Python (Automation with batch files and scheduled tasks) <a href="https://www.e-education.psu.edu/geog485/node/143?fbclid=IwAR1Vqx-4F78HTdAd1rALBJCKcEYlF2nirJDmAJaVfLER3s15x_Hex_utgZ8">Site Web</a>

!> La base de donnée sous le nom de "E_reputation" et les collections seront disponible avec le projet dans repository github. 