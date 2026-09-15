# Frais, bribes et récompenses

Aerodrome distingue les frais issus des pools et les récompenses qui incitent les votes. Les frais abandonnés par les fournisseurs de liquidité dans une gauge sont envoyés vers FeesVotingReward.

BribeVotingReward reçoit des récompenses déposées de l’extérieur pour influencer les votes d’une époque. Les frais et les bribes sont ensuite attribués aux votants selon leurs checkpoints et leur poids sur le pool choisi.

Les contrats Reward et VotingReward enregistrent l’évolution des soldes et de l’offre. Comme le pouvoir veAERO décroît avec le temps, Voter.poke peut être nécessaire pour actualiser les checkpoints.

Le rendement affiché par une interface dépend donc de l’époque, du pool, des votes, des dépôts externes et du moment de la réclamation.

→ [Chapitre suivant : émissions et gouvernance](06-emissions-et-gouvernance.md)
