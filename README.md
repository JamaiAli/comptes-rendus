# 📚 Comptes Rendus

Mes comptes rendus de TP, TD et fiches, classés par matière.

## Informatique Fondamentale

- [Chaînes de Markov et Simulation à événements discrets](matieres/informatique-fondamentale/chaines-markov/)
- [Mécanismes internes et fonctionnement des SGBD Relationnels](matieres/informatique-fondamentale/sgbd-relationnels/)
- [Mise à niveau système/réseau / Outils de déploiement](matieres/informatique-fondamentale/systeme-reseau-deploiement/)
- [Programmation Java Avancée](matieres/informatique-fondamentale/java-avance/)

## Sécurité Informatique

- [Administration de réseaux](matieres/securite-informatique/administration-reseaux/)
- [Codes correcteurs d'erreur](matieres/securite-informatique/codes-correcteurs/)
- [Rétro-Ingénierie et Forensique](matieres/securite-informatique/retro-ingenierie-forensique/)
- [Sécurité réseau](matieres/securite-informatique/securite-reseau/)
- [Sécurité système](matieres/securite-informatique/securite-systeme/)
- [SOC : Security Operation Center](matieres/securite-informatique/soc/)

---

## Comment ajouter un document

1. Dépose ton fichier (PDF, image, `.md`...) dans le dossier de la matière concernée, sous `matieres/<catégorie>/<matière>/`.
2. Ouvre le `README.md` de cette matière et ajoute une ligne de lien dans la bonne section (`TP`, `TD` ou `Fiches`), par exemple :
   ```md
   - [TP1 - Introduction](TP1-introduction.pdf)
   ```
3. Commit et push sur GitHub — le site se met à jour automatiquement (GitHub Pages).

## Ajouter une nouvelle matière

1. Crée un dossier dans `matieres/<catégorie>/<nom-matiere>/` avec un `README.md` (voir les matières existantes comme modèle).
2. Ajoute un lien vers ce dossier dans `_sidebar.md` et dans ce `README.md`.
