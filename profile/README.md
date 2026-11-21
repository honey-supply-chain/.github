# Honey Supply Chain

Prototyp einer Blockchain-basierten Honig-Lieferkette mit Smart-Contract gesteuertem Preismodell.

Die Repositories dieser Organisation gehören zur Masterarbeit

> **Transparente Blockchain-basierte Preisbildung in Agrar-Lieferketten**
> Philipp Wildzeiss, Masterstudiengang Cloud Computing Engineering, Hochschule Burgenland, 2026

Die Arbeit untersucht, wie ein Smart-Contract gesteuertes Preismodell die Qualität und Transparenz der Bienenhaltung quantifizierbar in den Endproduktpreis integrieren kann. Sie folgt dem Design Science Research nach Peffers et al. (2007). Der Prototyp wurde in einer Fallstudie mit einem Imker in zwei Iterationen evaluiert.

## Repositories

| Repository | Inhalt |
|---|---|
| [honey-supply-chain](https://github.com/honey-supply-chain/honey-supply-chain) | Smart Contracts (Solidity, Hardhat): ActorRegistry, SupplyChain, QualityIndex, PricingModel, HoneyToken (ERC-1155), ProductGateway |
| [honey-supply-chain-dapp](https://github.com/honey-supply-chain/honey-supply-chain-dapp) | dApp für Imker:innen und öffentliche Produktansicht (viem, wagmi, MetaMask) |
| [honey-supply-chain-simulator](https://github.com/honey-supply-chain/honey-supply-chain-simulator) | Java-Simulator für Labor, Zertifizierungs- und Prämierungsstelle sowie Sensordaten |
| [honey-supply-chain-evaluation](https://github.com/honey-supply-chain/honey-supply-chain-evaluation) | Systemdaten der Fallstudie und der technischen Messläufe |
| [honey-supply-chain-pricing-model](https://github.com/honey-supply-chain/honey-supply-chain-pricing-model) | Python-Simulation des Qualitätsindex und des Preismodells |

Der in der Fallstudie eingesetzte Stand ist je Iteration mit einem Tag markiert (`case-study-iteration-1`, `case-study-iteration-2`).

## Hinweis

Der Prototyp läuft im Sepolia-Testnetz und dient ausschließlich Forschungszwecken. Er ist nicht für den produktiven Einsatz vorgesehen.
