# Espace de collaboration IA — ChatGPT + Claude

Cet espace sert à résoudre des problèmes et à préparer des projets avec **deux analyses indépendantes**, puis à comparer les réponses.

## Situation
- Dépôt GitHub : `damsmeca/Dams`
- Branche de travail commune : `collaboration-ia`
- La branche `main` conserve l'ancien projet et ne doit pas être modifiée sans accord explicite.
- Les IA ne communiquent **pas directement ni automatiquement** entre elles. GitHub sert de relais lorsque l'utilisateur lance une étape.

## Rôles
1. **Utilisateur :** choisit le problème, donne le contexte, prend les décisions.
2. **ChatGPT :** reformule le besoin, propose une analyse et une solution, évalue les arguments et relit les propositions de Claude.
3. **Claude Code :** effectue une analyse indépendante, questionne la solution initiale et peut produire du code ou des documents si demandé.
4. **Utilisateur :** choisit la solution et autorise les modifications importantes.

## Déroulement d'une mission
1. Écrire le problème, le résultat attendu et les contraintes dans une fiche de mission (voir `missions/MODELE.md`) ou une issue GitHub.
2. Obtenir une première proposition d'une IA.
3. Demander une revue indépendante à l'autre IA en lui donnant le lien vers la mission.
4. Comparer les convergences, désaccords, hypothèses non vérifiées et risques.
5. Décider des prochaines actions **avec l'utilisateur**.
6. Archiver une synthèse et les sources éventuelles sur GitHub.

## Règles
- Ne jamais présenter une réponse de l'autre IA comme une réponse reçue directement.
- Signaler explicitement les faits non vérifiés, les incertitudes et les désaccords.
- Pour les informations factuelles importantes, indiquer des sources vérifiables et leur date.
- Ne pas inventer de résultats de tests, d'accords ou d'actions effectuées.
- Ne pas publier de mots de passe, de clés API, ni d'informations personnelles sensibles dans GitHub.
- Ne pas modifier la branche `main` ni fusionner des propositions sans autorisation de l'utilisateur.
- Utiliser des branches ou fichiers distincts pour les modifications concurrentes.

## Première utilisation
Ouvrir `missions/MODELE.md` pour préparer un nouveau problème. Claude Code peut consulter ce fichier dans le dépôt, sur la branche `collaboration-ia`.
