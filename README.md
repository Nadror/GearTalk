# GearTalk

## Technologies étudiées

- Metamask, Permet de créer un wallet basé sur ETH, application ou extension broswer

- Ganache-ui, Outil utilisé pour créer une blockchain en local pour dév nos smart-contracts sur la blockchain ETH en one-clic (UI/CLI)

- Truffle, Outil pour dév / débug / compiler nos smart-contracts (extension VSCode)


## Création d'un smart-contract :

```sol
pragma solidity >=0.4.20;

contract Testapp {
    string public name = "test";
}
```
## Déploiement sur notre blockchain en local

- Créer un script pour compiler notre smart contract avec Truffle et déployer sur notre blockchain Ganache puis voir le solde se baisser

## Pour comprendre
- https://github.com/dappuniversity/starter_kit
- https://www.dappuniversity.com/
