# 3. Moteur de plugins et API

Le moteur de plugins est le contrat d extension de Remix. Un plugin declare ses capacites, demande des services puis publie des vues ou des actions dans l IDE. Les plugins natifs s appuient sur les bibliotheques communes ; des plugins externes peuvent communiquer avec le moteur par les interfaces prevues. Cette architecture isole l interface utilisateur de fonctions comme la compilation, le deploiement, le stockage ou la console. Les evenements et les appels asynchrones permettent de synchroniser plusieurs panneaux autour d un meme projet. La richesse de l API implique une discipline de versionnage : une modification de contrat peut affecter l IDE, l extension et les integrations. Les limites de ce chapitre sont documentaires : aucun plugin n a ete installe ni execute.

Suite : [espaces de travail](04-workspaces-fichiers.md).
