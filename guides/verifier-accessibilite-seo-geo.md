# Vérifier l’accessibilité d’un site aux moteurs et aux réponses IA

Une méthode de diagnostic pour une petite équipe. L’objectif est de produire des constats vérifiables avant de demander des corrections, puis de mesurer ce qui change.

**Auteur : équipe Ryze · Version du 17 octobre 2026.**

## 1. Choisir un échantillon explicite

Retenir l’accueil, une page de service, une page de contenu, une page de contact et, si elles existent, leurs variantes linguistiques. Noter les URL exactes. Élargir ensuite aux autres pages indexables du sitemap et conserver le nombre de pages réellement contrôlées. Un échantillon ne permet pas d’affirmer que tout le site est conforme.

## 2. Recueillir les preuves

| Contrôle | Méthode | Preuve à garder |
|---|---|---|
| Accès public | Ouvrir la page sans session ; vérifier la réponse réseau et les redirections. | URL de départ, URL finale, statut HTTP, date. |
| Exploration | Lire les règles robots.txt pour les robots concernés ; examiner les éventuels blocages du serveur ou du CDN. | Règle applicable et résultat du contrôle d’accès. |
| Indexabilité souhaitée | Vérifier les directives robots dans le HTML et les en-têtes HTTP. Confirmer que cette page est destinée à être publique. | Directive observée et intention du propriétaire. |
| URL de référence | Examiner la canonical et les éventuels doublons. Vérifier que la référence correspond bien au contenu. | Canonical déclarée et résultat de la page cible. |
| Découverte | Vérifier les liens internes et la présence des pages indexables dans le sitemap. | Page source du lien ou entrée du sitemap. |
| Contenu principal | Lire ce qui est effectivement rendu : offre, explications et conditions doivent être compréhensibles. | Capture ou extrait daté, avec URL. |
| Identité | Comparer nom, activité, contact et identité éditoriale entre le site et ses profils officiels. | Les deux informations en conflit, sans choisir arbitrairement laquelle est vraie. |
| Affirmations | Pour chaque chiffre ou résultat présenté, retrouver sa source, sa période et son périmètre. | Référence d’origine ; mention « non vérifié » si elle manque. |
| Données structurées | Vérifier leur syntaxe et leur correspondance avec le contenu visible ; utiliser le type adapté. | Résultat de validation et exemple concerné. |
| Mesure | Relever les données disponibles avec leurs dates et leurs définitions. | Source, période, filtres, fraîcheur et éventuelles lacunes. |

Un statut 200 démontre une réponse HTTP, pas une indexation. Une visite de robot ne démontre pas qu’un assistant a cité la page. Une mention sur un profil que l’on gère n’est pas une recommandation éditoriale indépendante.

## 3. Décrire une correction sans perdre le contexte

Pour chaque constat, conserver :

- un identifiant stable et la page concernée ;
- l’observation, sa date et la preuve ;
- l’impact possible, distinct d’un impact déjà mesuré ;
- la correction proposée et son responsable ;
- le critère de vérification et le statut ;
- la date de livraison, puis la mesure après un délai adapté.

**Exemple entièrement fictif :** la page `https://example.com/service` redirige vers l’accueil alors qu’un profil officiel la recommande encore. Le dossier conserve le lien externe, la chaîne de redirection et l’intention attendue. La vérification après correction porte d’abord sur l’accès à la bonne ressource. Un éventuel effet sur le trafic se mesure séparément.

## 4. Mesurer sans attribuer trop vite un gain

Choisir une question : davantage de visiteurs qualifiés, davantage de demandes pertinentes, ou moins d’erreurs d’exploration. Définir l’indicateur et sa période avant le changement. Documenter aussi les autres modifications, campagnes et variations saisonnières.

Comparer des périodes de même durée et de composition comparable. Lorsque le volume le permet, conserver un groupe de pages comparable sans intervention. Avec peu de données ou plusieurs changements simultanés, le résultat peut rester non concluant. Ne pas transformer une hausse isolée en preuve de causalité.

## 5. Adapter la veille au besoin

Une page inchangée n’a pas besoin d’être résumée à nouveau. Conserver les sources déjà lues, dédupliquer les URL, relever les différences et ne faire analyser que les nouveautés utiles. Les contrôles HTTP et les compteurs peuvent être calculés sans modèle de langage.

Sur un forum, une nouvelle technique est une piste à tester. Vérifier la documentation du service concerné et rechercher une preuve reproductible avant de modifier le site.

## Sources pour approfondir

- [Google : fonctionnalités IA et sites web](https://developers.google.com/search/docs/appearance/ai-features). Les fondamentaux SEO restent applicables ; aucun balisage spécial ne garantit l’apparition dans une réponse IA.
- [Google : rôle de robots.txt](https://developers.google.com/search/docs/crawling-indexing/robots/intro). Contrôler l’exploration et contrôler l’indexation répondent à des mécanismes différents.
- [Google : URL canoniques](https://developers.google.com/search/docs/crawling-indexing/consolidate-duplicate-urls). Choisir une référence cohérente pour des contenus identiques ou proches.
- [Google : règles relatives au spam](https://developers.google.com/search/docs/essentials/spam-policies). Les liens et contenus doivent servir les personnes qui les consultent.

Cette checklist est un point de départ, pas une certification ni un audit de sécurité. Les données privées, mots de passe et informations clients doivent rester hors des comptes rendus publics.
