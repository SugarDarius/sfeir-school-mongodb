<!-- .slide: class="sfeir-basic-slide"-->
# Aggrégation Pipeline
<br>
<div class="center">
  <img class="aggregation-pipeline__pipeline" src="../assets/images/aggregation-pipeline.gif"/>
</div>
<div>
<br><br>
<ul>
  <li>Une aggrégation pipeline est composée de <span class="important">stages<span></li>
  <br>
  <li>Chaque stage est composé d'un ou plusieurs <span class="important">opérateurs</span></l<<i>
</div>

##==##

<!-- .slide: class="sfeir-basic-slide"-->
# Les stages les plus classiques
<br>
<div class="flex-row">
  <div class="circle bold">$match</div>
  <div class="circle bold">$project</div>
  <div class="circle bold">$skip</div>
  <div class="circle bold">$limit</div>
  <div class="circle bold">$sort</div>
</div>
<br>
<div class="flex-row">
  <div class="circle bold">$unwind</div>
  <div class="circle bold">$group</div>
  <div class="circle bold">$lookup</div>
  <div class="circle bold">$addFields</div>
</div>
<br>
Note:
Il en existe bien plus que cela! La documentation est votre meilleur amie. Ici se trouve les plus courants.


documentation: https://docs.mongodb.com/manual/meta/aggregation-quick-reference/
 
##==##

<!-- .slide: class="sfeir-basic-slide"-->
# Les opérateurs les plus classiques
<br>
<div class="flex-row">
  <div class="circle bold">$add</div>
  <div class="circle bold">$addToSet</div>
  <div class="circle bold">$push</div>
</div>
<br>
<div class="flex-row">
  <div class="circle bold">$avg</div>
  <div class="circle bold">$sum</div>
  <div class="circle bold">$multiply</div>
</div>
<br>


