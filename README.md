# ERC-20 Token - MyToken

Un simple token ERC-20 développé avec Solidity, utilisant le standard OpenZeppelin.

## Fonctionnalités

- Création d'un token ERC-20 avec un supply initial de 1 million de tokens.
- Fonction de minting (création de tokens supplémentaires) réservée au propriétaire.
- Fonction de burning (destruction de tokens) permettant aux utilisateurs de détruire leurs propres tokens.

## Déploiement

Ce projet est prêt à être déployé sur un réseau Ethereum testnet comme Sepolia. Suivez les instructions dans `scripts/deploy.js` pour le déployer.

## Installation

Clonez ce projet et installez les dépendances :

git clone https://github.com/VegaCrypto4/erc20token.git cd erc20token npm install


## Tests

Pour tester le contrat, exécutez la commande suivante :

npx hardhat test