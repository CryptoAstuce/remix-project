# 5. Debogage, reseaux et deploiement

Le debogueur de Remix exploite la trace d une transaction et les correspondances entre bytecode et sources. Il peut replacer l execution dans le contrat, afficher la pile et suivre les variables lorsque les metadonnees sont disponibles. Le parcours de deploiement suit une autre frontiere : un provider fournit le reseau, un compte signe et une transaction devient observable. Les plugins de test, de verification et d interaction reutilisent ces services pour garder une experience coherente. Les erreurs de RPC, de chain ID, de gas ou de source map restent des cas de production a traiter explicitement. Les traces ne remplacent pas une revue de securite ni une verification formelle. Les limites de ce chapitre sont documentaires : aucune transaction n a ete envoyee.

Suite : [qualite et limites](06-qualite-limites.md).
