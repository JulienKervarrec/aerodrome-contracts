# Pools et swaps

Le contrat Pool porte la liquidité d’une paire. Les pools volatiles utilisent une courbe de produit constant proche d’Uniswap V2. Les pools stables utilisent une courbe cubique adaptée aux actifs dont le prix doit rester proche.

Le Router compose plusieurs pools et prend en charge les échanges, dépôts et retraits de liquidité. Il propose aussi des zaps, y compris pour des tokens à frais de transfert, mais cette compatibilité ne signifie pas que tous les tokens exotiques sont sûrs.

PoolFees sépare les frais de trading des réserves. Cette séparation est importante pour comprendre la valeur des LP tokens et le chemin suivi par les frais vers les récompenses de vote.

La spécification signale une limite : l’invariant stable peut subir de petites erreurs d’arrondi temporaires.

→ [Chapitre suivant : veAERO et VotingEscrow](03-veaero-et-votingescrow.md)
