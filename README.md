
# eJPTv2 Review FR
## cette review est en troix parties

- Les cours et le PATH 

- Comment préparer l'exam hors cours de l'INE

- L'examen 

- Ce qui manque à la certification


### Les cours et Le PATH

Après votre paiement, vous obtiendrez l'acces au PATH 'Penetration Tester student' de l'INE. Les cours sont dirigés par Josh Mason, mais principalement enseignés par Alexi Hamed, également connu sous le nom de @Hackersploit. Le parcours dure 148 heures et est très complet. Vous aborderez tous les aspects fondamentaux du pentesting à travers des vidéos explicatives, suivies de travaux pratiques dans un laboratoire pour mettre en pratique ce que vous venez d'apprendre. Vous disposerez d'un fichier PDF pour chaque laboratoire, afin de prendre des notes. Personnellement, j'ai enregistré toutes mes notes dans une base de données personnelle, car c'est ma méthode de travail. Je recommande l'utilisation de l'outil Notion pour ce type de prise de notes.

Comme mentionné précédemment, le contenu des cours est très complet. Vous commencerez par une section sur les technologies d'évaluation, qui, pour être honnête, est quelque peu inachevée. Le module sur la « Collecte d'Informations » est particulièrement intéressant, car il traite de toutes les méthodes de recherche sur des sources ouvertes pour obtenir des informations sur votre cible via internet (animé par Hackersploit).

La section la plus captivante est la troisième, intitulée « Test de Pénétration sur les Hôtes et Réseaux ». Cette section à elle seule pourrait suffire pour réussir l'examen. Vous y apprendrez à comprendre et à utiliser le framework Metasploit, qui occupe une place centrale dans cette certification. Vous passerez en revue tous les aspects d'un test de pénétration, notamment le scan actif via nmap et ses divers scripts (NSE), l'énumération des services réseau tels que smb, ssh, ftp, rdp, mysql, apache, smtp, et j'en oublie sûrement. Vous apprendrez ensuite comment exploiter ces vulnérabilités pour accéder à une machine ou à un serveur après les avoir identifiées. Dans la même veine, il y a une section consacrée à la post-exploitation, qui inclut l'énumération et les élévations de privilèges sous Linux et Windows, diverses techniques de persistance, du pivotage avec Meterpreter, ainsi qu'une petite partie sur l'effacement des traces. Vous serez également initié à des attaques telles que l'empoisonnement ARP et les attaques WiFi. En ce qui concerne l'exploitation web, le parcours part vraiment de zéro, alors prenez des notes détaillées sur les attaques par force brute sur les formulaires de connexion http-post avec l'outil Hydra, car cela peut s'avérer utile lors de l'examen. En réalité, cette certification ne se penche que très rarement, voire jamais, sur l'exploitation manuelle des vulnérabilités, ce qui est dommage, car parfois, vous pouvez exploiter une vulnérabilité sans vraiment comprendre pourquoi vous avez obtenu une exécution de code à distance (RCE).

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

