# scouts_camps_data
Harmonization of the data of the youth camps, so that the emergency services can arrive quicker on scene.

The purpose of this repository is only to share my knowledge of the problem, as I am completely external to the issue and therefore do not have a proper understanding. Poppy does not subsitutes itself to existing people & projects, but can bring the missing link if needed: user-centered design, analysis, development, expertise for notifications, ... 

**Situation rêvée**

- Janvier 2020, la chef de la 31ème unité de Lessines encode les informations sur le camp qu’elle organise en juillet à Habay. Le service communal est automatiquement avisé par e-mail. Celui-ci consulte les données des camps de sa commune et peut interagir avec les unités (demandes de précisions), approuver ou refuser la demande.
- Les zones de police, la province et la zone de secours peuvent consulter les informations  sous forme de fiches, de listes et de cartes. 
- Les fédérations peuvent également consulter les données de leurs unités.
- Au cours des mois qui précèdent le camp, la chef peut modifier ses données directement dans l’interface, évitant ainsi des échanges de mails. Au début du camp, elle met les dernières données à jour (numéros de contact, …).
- En cas d’appel d’urgence, les centres d’appel et dispatchings ont accès à la liste dans un outil unique, leur permettant de disposer rapidement des informations de contact et d’accès aux camps.
- A tout moment, chacun peut exporter les données qui le concerne  en format Excel et KML pour l’utiliser dans ses outils (ex : ICMS, Be-Alert, QGIS, Google Sheets, …) et pour disposer d’une copie offline en cas de panne.
- Si tous les camps doivent être avertis (ex : interdiction de feux), l’appui sur un simple bouton leur envoie l’information par SMS.

**Bénéfices**
- pour les services de planification (communaux, zonaux, provincial)
  - Gain de temps
  - Toutes les données sous la même forme, dans le même outil
  - Évite les échanges de mails
  - Historique

- pour les centres d’appel et les dispatchings 
  - Gain de temps dans la recherche d’informations
  - Informations à jour (contacts & accès)

 - pour les mouvements de jeunesse : encodage unique
   - Gain de temps
   - Une seule manière d’encoder pour toute la/les province(s)
   - Récupérer des informations d’une année à l’autre (tant du côté des scouts : personnes de contact, que pour les lieux de camps : accès, propriétaires, …)
   - Consultation & analyse des données par les fédérations (ex : qui est responsable de tel camp)
   - Possibilité de mettre à jour facilement
   - Recevoir assistance pompier / médicale / police plus rapidement

**Solutions possibles**

*Solution complète*
 - Coût élevé
 - Financement… à plusieurs ?
 - Cahier de charges / marché public
  
*Appli “CampCheck”*
 - But : avoir de l’info valide sur la situation réelle des camps
 - Ne change rien au travail en amont
 - Au début du camp, le responsable se géolocalise puis encode quelques détails
 - Pour vous : p. ex. sous forme de Google Sheet et de carte

*APIs*
 - travailler sur base des API des différentes fédérations, agrégées
...
