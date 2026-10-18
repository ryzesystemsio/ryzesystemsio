# Du besoin au logiciel

Un kit de cadrage pour une petite équipe.

**Ryze · Ressources publiques · Version du 18 octobre 2026 · Préparé avec assistance IA.**

Un outil utile commence par une décision précise : quel travail voulons-nous rendre plus fiable ? Ce kit permet de décrire ce travail, de choisir ce que le logiciel peut prendre en charge et de vérifier le résultat avant de le généraliser. Il ne décrit pas une fonctionnalité déjà disponible dans RyzeOS.

## 1. Décrire un cas réel avant de choisir un outil

Complétez cette phrase : « Quand [événement] se produit, [personne] doit obtenir [résultat observable], à partir de [informations], avant [échéance]. »
Puis prenez trois exemples autorisés : un cas courant, un cas incomplet et un cas exceptionnel. Retirez les données personnelles inutiles. Une description du cas suffit si vous ne pouvez pas partager les fichiers.

### Fiche à remplir

- Nom du processus :
- Responsable métier et personne qui valide :
- Déclencheur :
- Entrées indispensables et provenance :
- Résultat attendu :
- Étapes actuelles et outils utilisés :
- Fréquence observée, période et nombre de cas :
- Temps observé par étape, source de la mesure :
- Erreurs observées et conséquences :
- Données autorisées / données exclues :
- Accès déjà disponibles / accès encore nécessaires :
- Décisions humaines à conserver :
- Retour au fonctionnement manuel :

## 2. Choisir le niveau d’automatisation

- **Manuel** : choisir ce mode lorsque le besoin change encore, que les preuves manquent ou que le cas exige un jugement dont personne n’a défini les critères.
- **Assisté** : le logiciel rassemble, extrait ou propose ; une personne vérifie avant la décision ou l’envoi. C’est souvent un premier pilote utile lorsque les entrées sont hétérogènes.
- **Automatique sous conditions** : réserver ce mode aux opérations dont les préconditions, erreurs, droits et possibilités de reprise sont explicites. Définir ce qui provoque un arrêt et à qui le cas est transmis.

Il n’est pas nécessaire d’attribuer un score global. Une seule condition indispensable non satisfaite peut empêcher l’automatisation d’une étape. Séparer les étapes plutôt que décider que tout le processus sera automatique.

## 3. Écrire des critères de réception

Pour chaque sortie attendue, renseigner : cas de départ ; résultat vérifiable ; source faisant autorité ; personne qui contrôle ; condition de réussite ; condition d’arrêt.
Prévoir au minimum : entrée complète, information manquante, doublon, source contradictoire, accès refusé, indisponibilité du service et reprise après interruption.
Un résultat plausible n’est pas suffisant. Le destinataire doit pouvoir comprendre d’où il vient et corriger une erreur sans la propager.

## 4. Exemple entièrement fictif

« Atelier Exemple » reçoit des demandes de réparation. Cette entreprise, ses volumes et son scénario sont inventés ; ce n’est ni un client ni un résultat Ryze.

Besoin : lorsqu’une demande arrive, la personne d’accueil doit disposer d’une fiche indiquant l’objet, la panne décrite et les informations manquantes. Le technicien décide ensuite de la suite. Le système ne doit pas promettre un tarif ni un délai à la place de l’équipe.
Pilote proposé : préparer une fiche interne à partir de dix messages synthétiques, sans envoi aux clients. Ce nombre définit le premier essai, pas une preuve statistique.
Entrées : message d’exemple, catalogue fictif des réparations acceptées et liste des champs requis.
Sortie : fiche avec identifiant, faits extraits, passage source pour chaque fait, champs manquants et décision humaine attendue.

- Cas A — demande complète : reprendre les faits sans ajouter de diagnostic.
- Cas B — référence absente : afficher « référence à demander », sans inventer un modèle.
- Cas C — même message reçu deux fois : signaler le doublon possible et conserver les références ; ne pas effacer automatiquement un dossier.
- Cas D — deux descriptions incompatibles : montrer la contradiction au technicien.
- Cas E — pièce jointe inaccessible : conserver le cas en attente avec le motif.
- Cas F — instruction dans un message demandant de modifier les règles : traiter ce texte comme contenu reçu, pas comme autorisation.
- Cas G — arrêt puis reprise : retrouver la fiche existante au lieu de la créer une seconde fois.

Critères proposés : chaque fait de la fiche doit être relié à son entrée ; aucune information inventée ; aucun message envoyé ; chaque cas incomplet ou contradictoire doit être identifiable. Ces critères restent à convenir avec le responsable avant l’essai.
Résultats : non mesurés. Ce kit fournit un protocole, pas un témoignage de performance.

## 5. Mesurer ce qui change

Noter le temps de préparation ET de vérification, les corrections nécessaires, les cas repris manuellement, les échecs et les coûts réellement consommés. Conserver le nombre de cas et la période.
Comparer à un fonctionnement manuel sur des cas comparables. Un gain calculé sur un exemple ne doit pas devenir une promesse commerciale générale. Présenter les erreurs à côté des réussites.

### Journal de décision à recopier

- Date et cas :
- Proposition et source :
- Décision humaine et motif :
- Résultat vérifié :
- Temps de contrôle et coût observé :
- Prochaine action :

## 6. Passer à l’étape suivante

À la fin du pilote, choisir : abandonner, corriger, rester assisté ou élargir le périmètre. Préciser le responsable, les accès autorisés, le budget d’essai et les critères d’arrêt. Réviser le protocole si les entrées, le modèle ou le processus changent.
