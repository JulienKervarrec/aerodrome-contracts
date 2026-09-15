# Émissions et gouvernance

Minter produit les émissions d’AERO par époque. Le calendrier commence avec une émission hebdomadaire qui décroît, puis prévoit un régime de tail emissions lié à l’offre en circulation. RewardsDistributor traite séparément les rebases des positions verrouillées.

EpochGovernor peut ajuster l’émission future lorsque le régime terminal est actif. ProtocolGovernor utilise le pouvoir de vote issu des NFT veAERO pour contrôler certaines décisions, notamment la whitelist de tokens et la création de managed veNFTs.

La gouvernance n’est pas une simple couche administrative : elle modifie les paramètres qui déterminent les incitations économiques et les actifs acceptés. Les rôles et permissions doivent être lus avec PERMISSIONS.md.

Les limites importantes sont la dépendance aux fenêtres d’époque, aux rôles privilégiés et aux factories remplaçables.

→ [Chapitre suivant : périmètre et limites](07-perimetre-et-limites.md)
