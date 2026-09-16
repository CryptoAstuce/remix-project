# 1. Architecture de Remix Project

Remix Project reunit un IDE Ethereum, un moteur de plugins et des bibliotheques reutilisables. Le depot est un monorepo organise autour de `apps` pour les applications et de `libs` pour les composants partages. Cette separation permet de faire evoluer l IDE, l extension VS Code et les outils de fondation sans dupliquer les contrats d interface. Le moteur de plugins expose des services communs tandis que l interface compose des panneaux specialises. Les scripts Nx decrivent les dependances entre projets et rendent les taches observables. Le code source presente donc Remix comme une plateforme extensible, pas seulement comme un editeur Solidity. Les limites de ce chapitre sont documentaires : aucune installation, compilation ou execution n a ete realisee.

Suite : [compilation et AST](02-compilation-ast.md).
