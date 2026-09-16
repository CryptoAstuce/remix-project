# 4. Espaces de travail et fichiers

Remix organise le projet autour d un explorateur de fichiers et d un espace de travail persistant. Selon le contexte, les fichiers peuvent venir du navigateur, d un stockage local, d un espace partage ou d un dossier expose par remixd. Les plugins consultent cet espace par une API commune au lieu de manipuler directement le systeme de fichiers. Cette abstraction rend possible le meme parcours dans l IDE en ligne, le bureau et l extension VS Code. Elle impose aussi des limites de confiance : un dossier local ne doit etre expose qu avec une autorisation explicite et un perimetre compris. Les documents et configurations doivent rester synchronises avec la chaine de compilation. Les limites de ce chapitre sont documentaires : aucun fichier local n a ete ouvert ni modifie.

Suite : [debogage et deploiement](05-debug-deploiement.md).
