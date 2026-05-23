Focus sur l'Agent Oblivion
Au sein de l'architecture Allways, Oblivion est l'executeur securise et le centre de traitement logique du systeme. Son role unique est de servir de cerveau operationnel en prenant en charge la reflexion et l'analyse des requetes de l'utilisateur.

Pour accomplir ses tâches, Oblivion s'appuie sur deux composants techniques majeurs :

Le modele local Llama, qui lui fournit sa capacite de raisonnement et de comprehension algorithmique sans dependre d'un cloud externe.

L'outil de recherche DuckDuckGo, qui lui permet d'interroger Internet en temps reel afin d'enrichir ses reponses avec des donnees d'actualite.

Oblivion fonctionne selon un principe de confinement strict. Ses privileges d'execution sur le systeme d'exploitation sont reduits au minimum requis. Cette isolation numerique est une mesure de securite essentielle concue pour bloquer les tentatives d'injections de prompts indirectes, notamment lorsqu'un site web malveillant tente de corrompre la logique de l'IA lors du scraping de donnees.

Dans le flux de production, Oblivion intercepte les evenements transmis par le bus de messages. Il determine de maniere autonome s'il doit utiliser sa memoire locale ou declencher son module de recherche web pour repondre a la demande. Une fois son analyse terminee, il emet une proposition d'action qui est systematiquement transmise au reste de la Trinite pour validation avant toute diffusion finale.
