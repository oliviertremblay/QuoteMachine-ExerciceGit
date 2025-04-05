# QuoteMachine-ExerciceGit

Une petite application console collaborative en C# pour générer et gérer des citations inspirantes — conçue pour pratiquer le **GitHub Flow** en équipe.

---

## 🎯 Objectif

Développer une application C# console par itérations, en respectant le GitHub Flow :
- Création d'une branche par fonctionnalité
- Pull Request (PR) pour chaque ajout
- Chaque PR inclue la fonctionnalité et des tests unitaires pour prouver que **votre code fonctionne sans faille**.
- Revue de code par au moins une personne avant le merge

---

## 🎮 But du jeu

- Travailler en équipe pour compléter un maximum de fonctionnalités.
- Ajouter des tests unitaires pour prouver que **votre code fonctionne sans faille**.
- Respecter les bonnes pratiques Git et faire approuver vos PRs.
- Livrer un projet propre, bien structuré... et qui compile évidemment !

---

## 🧱 Structure du projet

  ```bash
QuoteMachine/
├── Program.cs           # Point d'entrée de l'application
├── Quote.cs             # Classe représentant une citation
└── QuoteManager.cs      # Classe qui gère les citations (à compléter)
```
---

## 🛠 Fonctionnalités à développer

Chaque fonctionnalité doit être développée dans **une branche distincte**, puis intégrée via une **pull request**.

### ➕ Fonctionnalités proposées :

| Branche                        | Fonctionnalité                                         |
|-------------------------------|--------------------------------------------------------|
| `feature/random-quote`        | Méthode pour retourner une citation au hasard         |
| `feature/add-quote`           | Ajouter une citation manuellement depuis la console   |
| `feature/menu`                | Créer un menu interactif dans `Program.cs`            |
| `feature/save-to-file`        | Sauvegarder les citations dans un fichier texte       |
| `feature/load-from-file`      | (Optionnel) Charger les citations à partir d’un fichier |

---

## ✅ Étapes recommandées

1. **Cloner le projet** et créer une nouvelle branche :
```bash
   git checkout -b feature/nom-de-votre-fonctionnalité
```
3. **Coder votre fonctionnalité localement**

4. **Pousser votre branche sur GitHub** :
```bash
   git push origin feature/nom-de-votre-fonctionnalité
```
6. **Créer une Pull Request** sur GitHub

7. **Demander une revue** à un collègue

8. **Une fois approuvée**, merger la PR dans `main`

---

## 👩‍💻 Bonnes pratiques

- Chaque membre devrait :
  - créer au moins une branche
  - approuver au moins une PR d’un autre
- Les commits doivent être clairs et descriptifs
- Testez vos fonctionnalités avant de soumettre une PR

---

## 💡 Exemple de citation

```text
"La vie, c’est comme une bicyclette, il faut avancer pour ne pas perdre l’équilibre." - Albert Einstein
```

---

## 🎓 Projet éducatif

Ce projet est conçu comme un exercice d’apprentissage collaboratif du **versionnage Git** et du **travail d’équipe sur GitHub**.

Bonne collaboration à tous et toutes ! 🚀
