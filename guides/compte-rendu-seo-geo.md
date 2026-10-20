# Compte rendu SEO/GEO : modèle et exemple rempli

**Ryze · Ressources publiques · Version du 20 octobre 2026 · Préparé avec assistance IA.**

Ce complément au [guide de vérification](verifier-accessibilite-seo-geo.md) aide à transmettre un constat avec sa preuve, sa correction proposée et son critère de réception. Copiez les rubriques utiles pour votre prochain audit.

Dupliquer cette fiche pour une passe bornée. Conserver les observations brutes séparément des interprétations. Laisser « inconnu » quand la preuve manque. Ce modèle ne déclenche aucune intervention et ne constitue pas une certification.


## 1. PÉRIMÈTRE ET DÉCISION ATTENDUE

- Identifiant de passe / version : ______
- Marque / domaine / responsable autorisé : ______
- Question à résoudre : ______
- Date, heure et fuseau des contrôles : ______
- URL contrôlées, une par ligne : ______
- Raison du choix de cet échantillon : ______
- Nombre réellement contrôlé / taille totale connue ou inconnue : ______
- Pages exclues et raison : ______
- Accès utilisé : public sans session / session autorisée, rôle seulement : ______
- Sources déjà disponibles réutilisées, avec date : ______
- Nouveaux contrôles nécessaires et raison : ______


## 2. OBSERVATION — UNE FICHE PAR PROBLÈME

- Identifiant stable du constat : ______
- URL exacte concernée / URL finale observée : ______
- Contrôle : accès / exploration / indexabilité souhaitée / canonical / découverte / contenu / identité / affirmation / données structurées / mesure : ______
- Méthode effectivement exécutée, outil et contexte : ______
- Résultat brut observé : ______
- Preuve : fichier ou URL, date de collecte, extrait minimal : ______
- Authentification requise pour lire la preuve : oui / non / inconnu : ______
- Constat factuel en une phrase : ______
- Ce que ce contrôle ne permet pas de conclure : ______
- Intention du propriétaire : confirmée, source / non confirmée : ______
- Impact constaté avec mesure et période, ou « non mesuré » : ______
- Impact possible, présenté comme hypothèse : ______
- Priorité proposée et motif concret, sans score automatique : ______
- Décision proposée : corriger / compléter les preuves / surveiller / aucune action : ______


## 3. CORRECTION À COORDONNER

- Action proposée et périmètre exact : ______
- Dépendances, contradiction à résoudre ou accès manquant : ______
- Responsable / destination de transmission autorisée : ______
- Identifiant d'action existant à rapprocher avant création : ______
- Critère de réception observable : ______
- Cas d'échec et reprise / retour arrière à convenir : ______
- État : observé / préparé / transmis / reçu / livré / vérifié / abandonné : ______
- Date et preuve de chaque transition réellement accomplie : ______

Un document préparé n'est pas une mission reçue. Une proposition de correction n'est pas une livraison. Conserver l'identifiant lors des nouvelles vérifications ; ajouter une observation datée plutôt que créer une nouvelle action identique.


## 4. MESURE APRÈS LIVRAISON

- Question mesurée : ______
- Métrique, définition, unité, source et filtres : ______
- Période de référence / période après livraison : ______
- Date de collecte / dernière date effectivement couverte par la source : ______
- Nombre de cas, pages ou observations concernés : ______
- Autres changements survenus pendant la comparaison : ______
- Résultat : amélioration / dégradation / inchangé / non concluant / non mesuré : ______
- Limites de la comparaison : ______
- Prochaine collecte au plus tôt / déclencheur d'une vérification anticipée : ______

Séparer les preuves suivantes : accès technique à une URL ; indexation observée dans une source identifiée ; mention dans une réponse IA conservée ; visite référente ; demande qualifiée. Ne pas déduire l'une de l'autre. Une valeur manquante reste manquante, elle ne devient pas zéro.
Pour un essai de réponse IA : conserver question exacte, service et modèle affiché s'il est connu, langue, contexte/session, date, réponse et URL citées. Une réponse sans citation vaut uniquement pour cet essai. Éviter d'envoyer des données privées dans les questions.


## 5. SYNTHÈSE ET REPRISE

- Constats vérifiés : ______
- Blocages : ______
- Corrections proposées / livrées / vérifiées, comptées séparément : ______
- Décision suivante et responsable : ______
- Prochaine passe utile, échéance ou fait nouveau attendu : ______
- Fichiers de preuve et liens accessibles au destinataire : ______
- Différence par rapport à la version précédente : ______


## DIFFUSION

Avant partage public, retirer secrets, cookies, identifiants personnels inutiles, données clients et détails internes. Une empreinte de fichier aide à identifier une version ; elle ne prouve pas à elle seule l'exactitude du constat. Le dossier interne et sa version publique peuvent avoir des contenus différents.

## Exemple rempli : une URL de service qui renvoie au mauvais contenu

ENTIÈREMENT FICTIF : entreprise, URL, dates d'observation, réponses HTTP et résultats ci-dessous sont inventés à des fins pédagogiques. Aucun contrôle réseau ni correctif n'a été exécuté pour cet exemple. Ce n'est pas un résultat Ryze ou client.


### PÉRIMÈTRE

Passe : DEMO-SEO-001, version 1.
Entreprise fictive : Atelier Démo. Domaine de démonstration : atelier-demo.invalid.
Question : un visiteur du profil public atteint-il la page de réparation annoncée ?
Échantillon : accueil et deux pages de service ; 3 URL sélectionnées pour vérifier un parcours. Taille totale du site inconnue. Aucune conclusion sur tout le site.
Observation fictive datée : 1 octobre 2026 à 09:00 Europe/Zurich.
Accès décrit par le scénario : lecture publique sans session.


### CONSTAT DEMO-SEO-001-A

Source du lien : https://profil-demo.invalid/atelier-demo
Lien affiché dans le scénario : https://atelier-demo.invalid/reparation
Chaîne de réponse fictive : /reparation → HTTP 301, Location: / → accueil HTTP 200.
Observation de contenu fictive : l'accueil présente l'entreprise mais aucune information sur le service demandé.
Preuve pédagogique : cette chaîne écrite est une donnée synthétique. Dans un dossier réel, joindre les réponses et une capture datées ; ici, il n'existe ni export réseau ni capture réelle.
Constat : le lien annoncé comme une page de réparation aboutit à l'accueil dans le scénario.
Limite : aucune preuve d'indexation, de classement, de citation IA ou de perte de visiteurs.
Intention fictive du responsable : conserver une page distincte pour cette prestation. Dans un audit réel, cette intention doit être confirmée par son propriétaire.
Impact mesuré : aucun.
Hypothèse : le détour peut empêcher un visiteur de trouver les informations attendues.
Priorité proposée : corriger ce parcours avant d'en accroître la diffusion ; il mène directement à une offre précise.


### PROPOSITION DE CORRECTION

État : préparé ; non transmis, non reçu, non livré.
Responsable : à désigner. Aucun nom de personne inventé.
Rapprochement : rechercher une action existante sur cette même URL avant toute création.
Option à faire valider : restaurer le contenu attendu sur /reparation ou modifier le lien vers une page équivalente vérifiée. Le choix dépend des URL et contenus réellement disponibles.
Critères de réception : le lien depuis le profil aboutit au service attendu ; l'offre et son contact sont visibles ; aucune boucle de redirection ; destination et intention confirmées. Les autres contrôles SEO restent à effectuer si le périmètre les requiert.
Retour arrière : à convenir avec le responsable de la livraison avant modification.


### VÉRIFICATION APRÈS LIVRAISON — VARIANTE FICTIVE

Le scénario suppose ensuite une livraison le 3 octobre à 10:00.
Observation fictive du 3 octobre à 10:30 : /reparation répond 200 et affiche bien la prestation attendue ; le lien du profil ouvre cette page. Le contenu attendu et l'arrivée depuis le profil sont vérifiés dans le scénario ; les autres critères restent à documenter. La réception complète reste donc en attente.
Dans un registre réel, seuls une livraison et un contrôle effectivement réalisés permettraient les états « livré » puis « vérifié ». Ces observations fictives ne doivent pas être enregistrées comme des actions réellement livrées.


### MESURE ET CONCLUSION

Indicateur envisagé : visites du profil vers la page de service, source et définition à convenir.
Référence avant livraison : indisponible. Série après livraison : indisponible.
Effet sur le trafic : non mesuré. Effet sur les demandes : non mesuré. Indexation et citations IA : non mesurées.
Décision : retenir uniquement le résultat technique décrit par le scénario, sans lui attribuer de gain commercial. Dans un cas réel, établir une collecte autorisée avant d'annoncer une progression.
