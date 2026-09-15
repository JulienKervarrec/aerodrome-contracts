# veAERO et VotingEscrow

AERO peut être verrouillé dans un NFT veAERO. Le poids de vote dépend de la quantité verrouillée et de la durée restante, avec une décroissance linéaire. La durée maximale est de quatre ans.

VotingEscrow distingue les NFT normaux, permanents, verrouillés et managed. Les opérations de fusion, division, délégation et retrait modifient les checkpoints de vote et les soldes historiques.

Un NFT permanent conserve son pouvoir de vote. Un NFT managed agrège plusieurs positions ; les dépôts deviennent verrouillés et les récompenses suivent ensuite les règles du managed NFT.

La lecture doit donc séparer solde de tokens, poids de vote, propriété du NFT et checkpoints temporels.

→ [Chapitre suivant : Voter et gauges](04-voter-et-gauges.md)
