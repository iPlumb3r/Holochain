# Holochain : Une initiative de 1er plan !

## Introduction
Suite à un <a href="https://github.com/iPlumb3r/Holochain/blob/master/HolochainNotBlockchain_FR.md">précédent article sur Holochain</a> visant surtout à mettre l'accent sur "ce en quoi #Holochain diffère de la #Blockchain", j'ai souhaité dans ce nouvel article :
* D'une part éclairer le spectre des différentes facettes de cette initiative
* D'autre part montrer la pertinence de chaque aspect du projet

## Une initiative "multi-facettes"
Holochain au sens strict n'est qu'un __protocole__ permettant de développer des applications distribuées ...   
... mais il est important de re-situer cela dans un contexte plus large en comprennant "à quoi il va servir".

Effectivement, par effet induit, ce __protocole__ va implicitement permettre l'avènement d'un nouvel Internet (Cf § "... NextNet ...") totalement distribué au sein duquel des applications "user-centric" pourront s'exécuter (Cf § "... hApp ...") et dont certaines d'entre-elles seront motorisées par un nouveau type de crypto-monnaies (Cf § ... monnaie ...) 

### Vers un "NextNet" totalement distribué
Tout d'abord, le réseau constitué par les __"Holo Nodes"__ est un réseau totalement distribué (et pas seulement décentralisé) qui fonctionne en mode "pair à pair" (P2P).
Autrement dit, dans un tel réseau, il n'y a PAS d'une part des _serveurs_ et d'autre part des _clients_ ; mais __uniquement__ des _noeuds_ qui jouent tous __exactement__ le même rôle (tantôt _client_ / tantôt _serveur_).    
![cen_dec_dis](https://github.com/iPlumb3r/Holochain/blob/master/images/centralized_decentralized_distributed.jpeg)

Pour des raisons de stabilité du réseau, à son lancement, les tout premiers __"Holo Nodes"__ sont uniquement des HoloPorts basés sur la même architecture technique et qui de plus ne peuvent seulement être achetés sur <a href="https://store.holo.host/">le store du site de Holo.host</a> ; mais cela n'est qu'une situation transitoire qui permet de faciliter la phase de "boostraping" en réduisant considérablement la charge de débogage.   

En effet, il sera prochainement possible de fabriquer soi-même son HoloPort à partir d'un Raspberry Pi ou d'un Intel NUC ou bien d'une autre plateforme technique. 
> Un groupe Telegram nommé <a href="https://t.me/holonode">DIY Holonode poolparty</a> est dédié à ce sujet.    

A terme il sera même possible d'installer le logiciel nécessaire pour transformer n'importe quel ordinateur ou même smartphone en __"Holo Node"__ !


### Vers la construction de hApps en mode "user-centric"
Ensuite __#Holochain__ permettra de développer pour ce réseau des applications totalement distribuées
* Les personnes ayant un "Holo Node" (que se soit un HoloPort original ou bien un "Holo Node" fabriqué et/ou paramétré par leur soins) pourront utiliser ces applications (dites "hApps") directement en mode P2P.   
* Ceux ne disposant pas de "Holo Node" pourront via la plateforme Holo.host (aka "HOLO") accéder à ces mêmes applications.   
(En contre-partie de ce service, Holo.host demandera 1% de commission en Holo Fuel aux créateurs de hApps).      
> HOLO est donc une passerelle entre le web "normal" (tel qu'on le connais aujourd'hui) et le futur Internet.   
  
Contrairement à l'approche __#Blockchain__ ("data-centric") qui nécessite d'exécuter de nombreuses applications sur la même __chaîne__ répliquée sur l'ensemble des noeuds du réseau, l'approche __#Holochain__ ("user-centric") met en oeuvre une __chaîne__ différente pour chaque application et même pour chaque utilisateur.

Il en résulte une scalabilité qui augmente proportionnelement avec le nombre d'utilisateurs, alors que c'est exactement le contraire avec une approche #Blockchain !!!   
![scalability](https://github.com/iPlumb3r/Holochain/blob/master/images/Scalability_Blockchain_Holochain.jpeg)

Et contrairement à la __#Blockchain__ qui requiert systématiquement un __consensus__ global - obtenu soit par PoW ("Proof of Work") soit par PoS ("Proof of Stake") - __#Holochain__ est "consensus less" (ou plus exactement est succeptible de fonctionner un niveau de __consensus__ que l'on peut ajuster en fonction de la criticité de l'application).

> Les hApps ont aussi vocation a être intérropérables entre-elles et a pourvoir être conçues "en mode Légo" comme on peux le lire dans l'article <a href="https://blog.holochain.org/introducing-crispr-a-happ-hacking-lab/">Introducing CRISPR</a> de Paul D'Aoust.


### Vers une galaxie de monnaies basées sur le crédit mutuel
Enfin, "last but not least", certaines hApps permettrons de mettre dans les mains de leur utilisateurs des monnaies d'un genre "hybride". A la fois :
* Très _ancien_ car basé sur un principe "vieux comme le monde" à un moment on l'argent (tel que nous le connaissons aujoud'hui) n'avait pas encore fait son apparition => je veux parler du principe de <a href="https://github.com/iPlumb3r/Holochain/blob/master/Holofuel/MutualCredit_FR.md">crédit mutuel/a> 
* Très _moderne_ car basé sur des méthodologies et technologies relativement récentes => je veux parler de la cyrptographie assymétrique et plus généralement des crypto-technologies
  
Contrairement aux crypto-monnaies "classiques" :
* d'une part, les unités de compte d'un crypto-"crédit mutuel" ne sont pas des "tokens" (au sens pièce numérique") mais plutôt des écritures dans un journal de comptabilité "en partie double" ou chaque transaction implique à la fois un débit ET un crédit du même montant ...   
... et dont la transation est signée par les 2 parties (et non uniquement par l'envoyeur, comme #Bitcoin par exemple)
* d'autre part la valeur d'un crypto-"crédit mutuel" est adossé à un actif économique réel (qu'il soit tangible ou intangible) : légume bio, produit vagan, électricité verte, textile éco-responsable, réputation lié à la qualité de service, ...

Les premiers crypto-"crédit mutuel" qui verront le jour seront ceux adossés à la passerelle HOLO : j'ai nommé le(s) Holo Fuel(s) car à priori il y en aura plusieurs ; chacun représentant une ressource informatique particulière :
* Capacité de stockage disque
* Puissance de calcul processus
* Bande passante réseau

Les crypto-"crédit mutuel" permettent de "flécher l'économie", au sein d'un territoire ou d'une tranche d'age, le long d'une filière industrielle ou agricole, ...

## Holochain coche toutes les cases

### Aspect Conceptuel
Bla bla ..

### Aspect Fonctionel
Bla bla ..

### Aspect Technique
Bla bla ..

### Aspect Stratégique
Bla bla ..

### Aspect Politique
Bla bla ..

### Aspect Opérationel
Bla bla ..
