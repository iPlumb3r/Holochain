# Holochain : Une initiative essentielle !

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
Ensuite __Holochain__ permettra de développer pour ce réseau des applications totalement distribuées
* Les personnes ayant un "Holo Node" (que se soit un HoloPort original ou bien un "Holo Node" fabriqué et/ou paramétré par leur soins) pourront utiliser ces applications (dites "hApps") directement en mode P2P.   
* Ceux ne disposant pas de "Holo Node" pourront via la plateforme Holo.host (aka "HOLO") accéder à ces mêmes applications.   
(En contre-partie de ce service, Holo.host demandera 1% de commission en Holo Fuel aux créateurs de hApps).      
> HOLO est donc une passerelle entre le web "normal" (tel qu'on le connais aujourd'hui) et le futur Internet décrit plus haut.   
  
Contrairement à l'approche __Blockchain__ ("data-centric") qui nécessite d'exécuter de nombreuses applications sur la même __chaîne__ répliquée sur l'ensemble des noeuds du réseau, l'approche __Holochain__ ("user-centric") met en oeuvre une __chaîne__ différente pour chaque application et même pour chaque utilisateur.

Il en résulte une scalabilité qui augmente proportionnelement avec le nombre d'utilisateurs, alors que c'est exactement le contraire avec une approche #Blockchain !!!   
![scalability](https://github.com/iPlumb3r/Holochain/blob/master/images/Scalability_Blockchain_Holochain.jpeg)

Et contrairement à la __Blockchain__ qui requiert systématiquement un __consensus__ global - obtenu soit par PoW ("Proof of Work") soit par PoS ("Proof of Stake") - __Holochain__ est "consensus less" (ou plus exactement est succeptible de fonctionner avec un niveau de __consensus__ que l'on peut ajuster en fonction de la criticité de l'application).

> Les hApps ont aussi vocation a être inter-opérables entre-elles et a pourvoir être conçues "en mode Légo" comme on peux le lire dans l'article <a href="https://blog.holochain.org/introducing-crispr-a-happ-hacking-lab/">Introducing CRISPR</a> de Paul D'Aoust.


### Vers une galaxie de monnaies basées sur le crédit mutuel
Enfin, "last but not least", certaines hApps permettrons de mettre dans les mains de leur utilisateurs des monnaies d'un genre "hybride". A la fois :
* Très _ancien_ car basé sur un principe "vieux comme le monde" à un moment où l'argent (tel que nous le connaissons aujoud'hui) n'avait pas encore fait son apparition => je veux parler du principe de <a href="https://github.com/iPlumb3r/Holochain/blob/master/Holofuel/MutualCredit_FR.md">crédit mutuel</a> 
* Très _moderne_ car basé sur des méthodologies et technologies relativement récentes => je veux parler de la cryptographie assymétrique (clé privé & clé publique) et plus généralement des crypto-technologies
  
Contrairement aux crypto-monnaies "classiques" :
* d'une part, les unités de compte d'un crypto-"crédit mutuel" ne sont pas des "tokens" (au sens pièce numérique") mais plutôt des écritures dans un journal de comptabilité "en partie double" ou chaque transaction implique à la fois un débit ET un crédit du même montant ...   
... et dont la transation est signée par les 2 parties (et non uniquement par l'envoyeur, comme #Bitcoin par exemple)
* d'autre part la valeur d'un crypto-"crédit mutuel" est adossé à un actif économique réel (qu'il soit tangible ou intangible) : légume bio, produit vagan, électricité verte, textile éco-responsable, réputation lié à la qualité de service, ...

Les premiers crypto-"crédit mutuel" qui verront le jour seront ceux adossés à la passerelle HOLO : j'ai nommé le(s) Holo Fuel(s) car à priori il y en aura plusieurs ; chacun représentant une ressource informatique particulière :
* Capacité de stockage disque
* Puissance de calcul processus
* Bande passante réseau

Fonctionellement, les crypto-"crédit mutuel" ont la capacité de "flécher" l'économie réelle grâce au mécanisme d'accouplement avec une ressource économique réelle ; que ce soit au sein d'un territoire ou d'une tranche d'age, le long d'une filière industrielle ou agricole, ...    
... ce qui totalement impossible avec les crypto-monnaies classiques car elle sont potentiellement acceptées partout.

Techniquement, si le concepteur de l'application le décide il est possible d'opérer des transactions sans AUCUN "fee" (car il n'y a pas de "miner" dans une architecture de type #Holochain), alors qu'avec une architecture de type #Blockchain en général et avec Ethereum en particulier les "fees" ont tendance à exploser lorsque le réseau monte en charge.



## Holochain coche toutes les cases
Dans cette section l'idée est de montrer que l'initiative #Holochain est pertinente sur l'ensemble des aspects susceptible de caractériser un projet.


### Aspect Finalité
> "Pourquoi Holochain a t-il été imaginé ?"

En bref, on peut dire que la raison d'être de l'écosystème <a href="http://metacurrency.org/">MetaCurrency</a> / <a href="http://holochain.org/">Holochain</a>  / <a href="http://holo.host/">HOLO</a> est de fournir les outils permettant à des __communautés qui partagent des valeurs__ ou des intérêts communs de __pouvoir se coordonner à large échelle__.

C'est un programme multi-disciplinaire, large et profond, aux ramifications multiples et variées ...
... qui tranche avec la simplicité de la finalité de #Bitcoin qui est d'être une réserve de valeur (aka "digital gold")

### Aspect Fonctionel
> "Qu'est-ce que Holochain ?"

Ce point à été largement abordé dans la 1ere partie de ce document.
On peut compléter

### Aspect Technique
> "Comment Holochain a t-il été implementé ?"

Holochain à fait l'objet d'un 1er prototype jettable en Go et d'un 2nd en Rust nommé "Redux" ...   
... puis ifnallement d'une version opérationelle, égalemen en Rust, nommé "RSM" (Refractored State Model)


### Aspect Stratégique
> "Quel sont les choix qui ont été fait ?"

Contrairement aux autre projets de la cryptosphère, l'équipe Holochain :
* à préféré la qualité du code livré aux délais de livraison
* à favorisé la communication auprès des développeurs plutôt qu'auprès des investisseurs
* se projette pluôt surle moyen-long terme plutôt que sur le court terme

Ces choix lui ont souvent été reproché, mais les résultats commence à être au rendez-vous

### Aspect Sponsoring
> "Qui supporte Holochain ?"

Si on se donne un peu la peine de chercher, on se rend compte que "mine de rien", Holochain est parfois seulement cité, parfois franchement supporté dans un grand nombre de documents émanant d'organisations de renommé mondiale. En voici quelques uns (une fois le document ouvert faite une recherche "plein texte" sur le mot "Holochain").

<table>
    <thead>
        <tr>
            <th>Organisation</th>
            <th>Document</th>
            <th>Commentaires</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>World Economic Forum (WEF)</td>
            <td><a href="https://www.weforum.org/agenda/2018/04/blockchain-survive-backlash-social-purpose-jem-bendall/">Blockchain is facing a backlash. Can it survive ?</a></td>
            <td>Holochain is identified as a project conscious about its total social impact</td>
        </tr>
        <tr>
            <td>United Nation (UN)</td>
            <td><a href="https://sphaera.world/wp-content/uploads/2018/03/Billions%20to%20Trillions.pdf">From Billions To Trillions</a></td>
            <td>An initiative dedicated to solve UN SDGs (Sustainable Development Goals)</td>
        </tr>
        <tr>
            <td>European Commision</td>
            <td><a href="https://publications.jrc.ec.europa.eu/repository/bitstream/JRC121675/jrc121675_dlt4good_scanning_the_european_ecosystem_online.pdf">Scanning the European Ecosystem of Distributed Ledger Technologiesfor Social & Public Good</a></td>
            <td>Appel à intéret</td>
        </tr>
        <tr>
            <td>H2020 Project</td>
            <td><a href="https://www.buyholo.net/pdf/horizon2020-interacting-decentralized-transactional-and-ledger-architecture-for-mutual-credit.pdf">Specification "Interacting Decentralized Transactional and Ledger Architecture for Mutual Credit"</a></td>
            <td>Spécification technique</td>
        </tr>
        <tr>
            <td>Club de Rome</td>
            <td><a href="https://r3dot0.medium.com/r3-0-2020-conference-exploring-the-third-thematic-thread-value-circularity-5c4a8cc62ec0">Exploring the Third Thematic Thread — Value & Circularity</a></td>
            <td>Colloque</td>
        </tr>
        <tr>
            <td>Bill & Melinda Gates Foundation</td>
            <td><a href="https://project1800.org/wp-content/uploads/2018/04/Project-1800.pdf">Project 1800 "Towards a market network for a water-secure world"</a></td>
            <td>Initiative dédiée à répondre au SDG n°6</td>
        </tr>
        <tr>
            <td>Bretton Woods 75 Committee</td>
            <td><a href="https://www.brettonwoods75.org/">Report "Exploring the future of global economics"</a></td>
            <td></td>
        </tr>
        <tr>
            <td>Bretton Woods 75 Committee</td>
            <td><a href="https://www.linkedin.com/pulse/bretton-woods-75-new-money-world-dr-mihaela-ulieru/">Report "A new money for a new world"</a></td>
            <td>Compte-Rendu</td>
        </tr>
    </tbody>
</table>

En plus de ces références documentaires :
* on peut aussi écouter Stephen Alexander (Un proche de Bill Gates) et Belinda Noakes (Une ex-Microsoft) actuelement affilié à <td><a href="https://digitalvaluecapture.com/">Digital Value Capture Academy</a></td> qui disent dans la video <a href="https://www.youtube.com/watch?v=Lu2lEv5D3FQ">Why Stephen waited for Holochain ?</a> que : 
> Holochain est LA technologie qu'ils attendaient depuis 20 ans !
* on peut aussi citer André Crojne (le talentueux créateur/développeur de Yearn Finance)
>  "This is something entirely new, and it isn't a blockchain, this is a new kind of decentralized beast, but I love it."      
> "Holochain is not really like anything I’ve seen before, so this code review won’t be quite like anything you’ve read from me before. The Holodchain scalable distributed computing model seems to be taking decentralization to a new level, but bloody hell, is this thing just too good to be true ?"


### Aspect Opérationel
> "Quel sont les utilisateurs de Holochain ?"

Ce sont des communautés de terrain qui ont généralement besoin d'une monnaie basée sur du crédit mutuel pour faire face aux besoins économiques de leur territoire.   
> Holochain a réalisé un grand nombre de "Hackatlons" depuis 2017 pour prototyper des solutions répondant à ces besoins    

Ex : <a href="http://www.darvoz.org/">darVOZ</a>

