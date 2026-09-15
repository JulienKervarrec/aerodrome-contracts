# Voter et gauges

Voter reçoit les votes des NFT veAERO et les associe aux pools. Un NFT peut voter une fois par époque, sauf pendant les fenêtres de distribution du début et de la fin d’époque.

Les votes déterminent la part d’émissions attribuée à chaque gauge. Une gauge est attachée à un pool et reçoit les dépôts de LP tokens. Les fournisseurs de liquidité renoncent alors aux frais directs du pool en échange d’émissions distribuées proportionnellement.

Voter crée aussi les gauges et les contrats de récompense associés, sous réserve des factories autorisées par FactoryRegistry. Une gauge peut être désactivée et ne reçoit alors plus d’émissions.

Le mécanisme relie donc trois droits différents : liquidité, pouvoir de vote et incitations externes.

→ [Chapitre suivant : frais, bribes et récompenses](05-recompenses-et-bribes.md)
