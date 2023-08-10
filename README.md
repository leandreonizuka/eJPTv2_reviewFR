
# eJPTv2 Review FR
## cette review est en troix parties

- Les cours et le PATH 

- Comment préparer l'exam hors cours de l'INE

- L'examen 

- Ce qui manque à la certification


## Les cours et Le PATH

Après votre paiement, vous obtiendrez l'acces au PATH 'Penetration Tester student' de l'INE. Les cours sont dirigés par Josh Mason, mais principalement enseignés par Alexi Hamed, également connu sous le nom de @Hackersploit. Le parcours dure 148 heures et est très complet. Vous aborderez tous les aspects fondamentaux du pentesting à travers des vidéos explicatives, suivies de travaux pratiques dans un laboratoire pour mettre en pratique ce que vous venez d'apprendre. Vous disposerez d'un fichier PDF pour chaque laboratoire, afin de prendre des notes. Personnellement, j'ai enregistré toutes mes notes dans une base de données personnelle, car c'est ma méthode de travail. Je recommande l'utilisation de l'outil Notion pour ce type de prise de notes.

Comme mentionné précédemment, le contenu des cours est très complet. Vous commencerez par une section sur les technologies d'évaluation, qui, pour être honnete n'a pas été faite en entier. Le module sur la « Information Gathering » est particulièrement intéressant, car il traite de toutes les méthodes de recherche sur des sources ouvertes pour obtenir des informations sur votre cible via internet (animé par Hackersploit).

La section la plus captivante est la troisième, intitulée «Host & Network Penetration Testing». Cette section à elle seule pourrait suffire pour réussir l'examen. Vous y apprendrez à comprendre et à utiliser le framework Metasploit, qui occupe une place centrale dans cette certification. Vous passerez en revue tous les aspects d'un test de pénétration, notamment le scan actif via nmap et ses divers scripts (NSE), l'énumération des services réseau tels que smb, ssh, ftp, rdp, mysql, apache, smtp, et j'en oublie sûrement. Vous apprendrez ensuite comment exploiter ces vulnérabilités pour accéder à une machine ou à un serveur après les avoir identifiées. Dans la même veine, il y a une section consacrée à la post-exploitation, qui inclut l'énumération et les élévations de privilèges sous Linux et Windows, diverses techniques de persistance, du pivotage avec Meterpreter, ainsi qu'une petite partie sur l'effacement des traces. Vous serez également initié à des attaques telles que l'empoisonnement ARP et les attaques WiFi. En ce qui concerne l'exploitation web, le parcours part vraiment de zéro, alors prenez des notes détaillées sur les attaques par force brute sur les formulaires de connexion http-post avec l'outil Hydra, car cela peut s'avérer utile lors de l'examen. En réalité, cette certification ne se penche que très rarement, voire jamais, sur l'exploitation manuelle des vulnérabilités, ce qui est dommage, car parfois, vous pouvez exploiter une vulnérabilité sans vraiment comprendre pourquoi vous avez obtenu une exécution de code à distance (RCE).

En ce qui concerne la difficulté des cours, ils restent au niveau très basique du pentesting. Cependant, je recommande tout de même d'avoir une connaissance préalable de l'utilisation du terminal, de l'environnement Linux et des bases solides en réseautique. Avant de suivre cette certification, j'avais travaillé sur TryHackMe, en particulier le parcours Junior Penetration Tester. Je ne peux que vous conseiller de faire ce parcours au préalable.

La majeure partie des cours est dispensée par Hackersploit, et c'est vraiment un plaisir de suivre ses enseignements. Personnellement, j'ai des difficultés avec l'anglais, surtout lorsque les gens parlent rapidement. J'avais donc un peu peur de manquer des informations, mais Hackersploit parle anglais de manière posée, ce qui m'a beaucoup aidé. Grâce à lui, j'ai même progressé en anglais. Pour vous donner une idée, j'ai commencé à regarder les vidéos avec des sous-titres en anglais, mais vers le milieu du parcours, je n'en avais plus besoin, tant le niveau d'anglais de Hackersploit est agréable. En ce qui concerne les explications techniques, elles sont également très claires. Hackersploit explique tout ce qu'il fait et ne va pas trop vite.

## Préparation Complémentaire avec CTF et Machines Pratiques

Je suis convaincu que les cours fournissent une base solide pour l'examen, cependant, pour renforcer mes compétences, j'ai choisi d'aller au-delà et de m'engager dans divers CTF en parallèle avec le parcours. Cette approche a grandement contribué à ma réussite à l'examen. Je m'étais déjà intéressé aux CTF avant de commencer la certification. Étant donné le manque d'accent mis sur l'exploitation manuelle dans le parcours, j'ai consacré beaucoup de temps à relever des défis sur RootMe. Cela m'a poussé à exploiter des vulnérabilités de manière manuelle et à mettre en pratique le principe « Lisez le foutu manuel ». 

Pendant la dernière semaine précédant l'examen, j'ai concentré mes efforts sur les challenges Boot2Root de TryHackMe et HackTheBox. Cela a été rendu possible grâce à l'accès gratuit temporaire à des machines retirées, qui s'est avéré très enrichissant. Je recommande de résoudre les machines suivantes avant l'examen :

### TryHackMe :

- [Basic Pentesting](https://tryhackme.com/room/basicpentestingjt)
- [Relevant](https://tryhackme.com/room/relevant)
- [Daily Bugle](https://tryhackme.com/room/dailybugle)
- [Ice](https://tryhackme.com/room/ice)
- [Blue](https://tryhackme.com/room/blue)
- [Skynet](https://tryhackme.com/room/skynet)
- [Tomghost](https://tryhackme.com/room/tomghost)
- [Brute It](https://tryhackme.com/room/bruteit)
- [GamingServer](https://tryhackme.com/room/gamingserver)
- [Anonymous](https://tryhackme.com/room/anonymous)
- [Blog](https://tryhackme.com/room/blog)
- [0day](https://tryhackme.com/room/0day)
- [Alfred](https://tryhackme.com/room/alfred)
- [Steel Mountain](https://tryhackme.com/room/steelmountain)
- [Hackparc](https://tryhackme.com/room/hackpark)

### HackTheBox : 

- [Timelapse](https://app.hackthebox.com/machines/Timelapse)
- [Devel](https://app.hackthebox.com/machines/Devel)
- [MonitorsTwo](https://app.hackthebox.com/machines/MonitorsTwo)
- [Pilgrimage](https://app.hackthebox.com/machines/Pilgrimage)

### VulnHub : 

- [DerpNstink](https://www.vulnhub.com/entry/derpnstink-1,221/)
- [Stapler 1](https://www.vulnhub.com/entry/stapler-1,150/) 
- [My Web Server](https://www.vulnhub.com/entry/my-web-server-1,463/)

## Expérience de l'Examen de Certification

L'environnement de l'examen est basé sur Guacamole. Mon environnement était stable, mais il y a des contraintes à considérer. Par exemple, j'ai voulu me connecter à un serveur via Evil-WinRM, mais l'outil n'était pas installé et l'environnement n'est pas connecté à Internet, ce qui signifie qu'il n'y avait pas de possibilité d'installer de paquets. Le manque d'accès VPN pour utiliser nos propres machines d'attaque a été une restriction, ce qui est dommage. J'ai ressenti des limitations dans mes choix d'attaques. Vous avez une marge de temps confortable, car vous disposez de 48 heures pour répondre aux questions, qui parfois vous aident à progresser dans le laboratoire.

Le contexte de l'examen est le suivant : vous vous trouvez dans une DMZ avec plusieurs hôtes à l'intérieur. Vous devez trouver un moyen d'accéder à plusieurs d'entre eux (dans mon cas, il s'agissait de 4 serveurs, dont 3 Windows et 1 Linux). En utilisant l'un de ces serveurs, vous devez établir une connexion avec Meterpreter pour pivoter sur un réseau interne (dans mon cas, un réseau Linux).

En vérité, la plupart des éléments de l'examen auraient pu être réalisés avec Metasploit, du moins une grande partie. Cependant, ce n'est pas toujours avantageux, car certains modules de Metasploit peuvent échouer, et vous ne pouvez pas toujours compter sur des preuves de concept depuis GitHub comme vous le feriez habituellement. Vous devez être capable de faire fonctionner vos modules. De plus, le fait de ne pas pouvoir copier-coller entre votre ordinateur hôte et l'environnement Guacamole ajoute une complexité. En ce qui concerne les vulnérabilités, la plupart d'entre elles étaient couvertes dans les cours, mais certaines ne l'étaient pas. C'est ici que l'expérience acquise lors des CTF m'a été d'une grande aide, car j'ai pu exploiter des vulnérabilités que je n'avais pas vues pendant le parcours.

Au total, j'ai passé 7 heures pour l'examen et j'ai obtenu la certification avec un score de 91% (le seuil de réussite est de 70%).

Mes conseils sont simples... Brute forcer moi ces services xD ! Plus sérieusement, l'examen se rapproche davantage de la réalité (du moins je le pense, n'ayant jamais fait de missions de pentesting). Ce n'est pas un CTF. Suivez bien votre méthodologie, prenez le temps de scanner minutieusement votre cible à l'aide de scripts Nmap pour obtenir autant d'informations que possible. Prenez des notes sur vos résultats, car il y a de nombreux hôtes à exploiter, et vous pourriez vous perdre dans les informations.

En ce qui concerne le pivoting, assurez-vous de repérer le point de pivot en consultant les cartes réseau à l'aide d'une commande comme `ifconfig` (dans le cas de Meterpreter). Il y aura forcément un point de pivot, ne le manquez pas. Essayez de tirer parti de Metasploit autant que possible, car les questions peuvent souvent tourner autour de Metasploit, ce qui vous aidera à répondre.

En termes de post-exploitation, n'oubliez pas de mettre en place de la persistance. Cela peut sembler évident, mais cela peut vous faire gagner du temps. J'ai personnellement gagné du temps en fermant mon navigateur Firefox qui chargeait un reverse shell. Heureusement, grâce à la persistance, je n'ai pas eu à refaire toute l'exploitation. Pour l'élévation des privilèges sur les hôtes Windows, dans mon cas je n'ai pas eu a élévers mes privilges, mais pour le système Linux, j'ai du passer par pluseiure phase d'élévation. N'oubliez pas de réutiliser les mots de passe que vous avez trouvés pour vous connecter en tant qu'utilisateur local.

Pour finir, utilisez les questions fournies comme des indices. À un moment donné, j'étais bloqué dans ma recherche du point de pivot, mais une question m'a orienté vers la vulnérabilité à exploiter, ce qui m'a permis de progresser.

## Lacune dans la Certification

Une lacune notable dans la certification réside dans l'absence d'une section consacrée au reporting. Je suis d'avis que le pentest ne se limite pas seulement à l'exploitation, mais également à la communication des résultats. Un rapport de pentest revêt une importance capitale, car il documente les vulnérabilités découvertes, les méthodes utilisées pour les exploiter, ainsi que les recommandations pour les résoudre. Il constitue une preuve concrète du travail accompli et de la valeur ajoutée en matière de sécurité.

Dans le contexte professionnel, les clients et les employeurs attendent généralement un rapport détaillé exposant clairement les problèmes de sécurité identifiés, ainsi que les mesures correctives suggérées. Un rapport bien structuré facilite la compréhension des enjeux et permet de prendre des décisions éclairées pour renforcer la posture de sécurité.

L'intégration d'une section dédiée au reporting dans la certification offrirait aux apprenants l'occasion de se familiariser avec la rédaction de rapports de pentest, un aspect fondamental de la profession de pentester dans la vie réelle. Cette inclusion pourrait également renforcer la compréhension de l'importance de la communication claire et concise des résultats de sécurité.

## Mot de Fin

La préparation à la certification de Ejptv2 exige une approche holistique. Des cours aux CTF en passant par l'expérience de l'examen, chaque élément contribue à développer des compétences solides en matière de sécurité informatique. Gardez à l'esprit que la persévérance, la pratique et la curiosité sont des atouts précieux dans ce parcours.

Bonne chance dans votre préparation et votre réussite à la certification !! 
