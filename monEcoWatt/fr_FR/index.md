# Changelog

[voir ici](changelog.md)

## Installation

Le plugin ne necessite l'installation d'aucune dépendance. il vous faudra uniquement un compte sur le site internet : [data.rte-france](http://data.rte-france.com/) afin d'obtenir vos propores identifiants pour récupérer la météo énergétique actualisée (un appel autorisé toutes les 15 minutes à API). 
<p></br></br></p>

<h3>Détails paramétrage :</h3>
<p></br></p>

 1. Rendez vous sur : [data.rte-france](http://data.rte-france.com/). Puis se connecter :
 <p align="center">
 <img src="../images/imgAide/01.png" width=90%></td>
 </p>

  2. S'incrire et se connecter après validation de votre compte par mail :
 <p align="center">
 <img src="../images/imgAide/02.png" width=90%></td>
 </p>

  3. Chercher Ecowatt à gauche dans la zone de recherche ou trouvez le parmis les services proposés :
 <p align="center">
 <img src="../images/imgAide/03.png" width=90%></td>
 </p>

  4. Abonnez-vous à l'API :
 <p align="center">
 <img src="../images/imgAide/04.png" width=90%></td>
 </p>

   5. Remplissez les infos demandés :
 <p align="center">
 <img src="../images/imgAide/05.png" width=90%></td>
 </p>
    6. Allez dans "Mes applications" :
 <p align="center">
 <img src="../images/imgAide/06.png" width=90%></td>
 </p>
    7. Copiez le "ID Client" et le "ID Secret", vous en aurez besoin par la suite :
 <p align="center">
 <img src="../images/imgAide/07.png" width=90%></td>
 </p>
    8. De retour sur Jeedom placez "ID Client" et le "ID Secret" dans les zone textuelle. Activer et rendez le visible dans un objet parent :
 <p align="center">
 <img src="../images/imgAide/08.png" width=90%></td>
 </p>
    9. Félicitation vous recevez la météo énergétique :) :
 <p align="center">
 <img src="../images/imgAide/09.png" width=90%></td>
 </p>



## Présentation

Ce plugin permetra la récupération de la météo énergétique afin d'aider les français à mieux consommer l'électricité.  
Véritable météo de l'électricité, monEcoWatt va vous permetre de récupérer en temps réel le niveau de conommation des français. A chaque instant, les vignettes vous permetrons de changer les informations du jour (sur 4 jours au maximum) puis une fourchette heure par heure vous indiquera les moments fort ou faible, afin d'adopter de bons gestes a tenir pour assurer le bon approvisionnement de tous en énergie.

 <p align="center">
 <img src="../images/imgMarket/00.png" width=100%></td>
 <p>1. Message du jour parmis 3 niveaux : (raisonnable, tendu, très tendu).</p>
 <p>2. Niveau du jour parmis 3 niveaux : (1, 2,3).</p>
 <p>3. Météo énergétique actuelle.</p>
 <p>4. Météo énergétique de demain.</p>
 <p>5. Météo énergétique à jour + 3.</p>
 <p>6. Météo énergétique à jour + 4</p>
 </p>
<p></br></br></br></p>

<table width=100%>
<tr>
  <tr>
    <td align="center">Dashboard : système raisonnable</td>
    <td align="center">Dashboard : système tendu</td>
    <td align="center">Dashboard : système très tendu</td>
  </tr>
  <tr>
    <td><img src="../images/imgMarket/01D.png" width=100%></td>
    <td><img src="../images/imgMarket/02D.png" width=100%></td>
    <td><img src="../images/imgMarket/03D.png" width=100%></td>
  </tr>
  </tr>
  <tr height="75px"/>
  <tr>
  <tr>
    <td align="center">Dashboard mobile : système raisonnable</td>
    <td align="center">Dashboard mobile : système tendu</td>
    <td align="center">Dashboard mobile : système très tendu</td>
  </tr>
  <tr>
    <td><img src="../images/imgMarket/01MD.jpg" width=100%></td>
    <td><img src="../images/imgMarket/02MD.jpg" width=100%></td>
    <td><img src="../images/imgMarket/03MD.jpg" width=100%></td>
  </tr>
  </tr>
  <tr height="75px"/>
  <tr>
  <tr>
    <td align="center">Mobile : système raisonnable</td>
    <td align="center">Mobile : système tendu</td>
    <td align="center">Mobile : système très tendu</td>
  </tr>
  <tr>
    <td><img src="../images/imgMarket/01M.jpg" width=100%></td>
    <td><img src="../images/imgMarket/02M.jpg" width=100%></td>
    <td><img src="../images/imgMarket/03M.jpg" width=100%></td>
  </tr>
  </tr>
 </table>
