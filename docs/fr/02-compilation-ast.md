# 2. Compilation, AST et analyse statique

Remix transforme les sources Solidity en artefacts exploitables par l IDE. Les bibliotheques de compilation dialoguent avec les versions du compilateur et exposent le bytecode, l ABI et les erreurs de syntaxe. L AST decrit la structure du programme sous forme d arbre ; le module d analyse peut alors parcourir contrats, fonctions, variables et expressions sans se limiter au texte. Les source maps relient les instructions generees aux positions du fichier, ce qui prepare le diagnostic et le debogage. Cette chaine separe clairement production d artefacts et interpretation par les plugins. Une version de compilateur ou un fichier de configuration inadapte peut toutefois rendre les sorties incompatibles. Les limites de ce chapitre sont documentaires : aucune compilation ni execution n a ete realisee.

Suite : [plugins](03-plugins-api.md).
