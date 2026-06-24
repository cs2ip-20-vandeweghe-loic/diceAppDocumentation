---
icon: lucide/rocket
---

# Tests de l’application Dice app

## Part 1 : Tests unitaires

Dans la route `/dice-type`, j’ai plusieurs tests unitaires :

- **getAll**
  - Permet de récupérer tous les `diceType`
  - Retourne un objet avec la liste complète

- **postErrorType**
  - Permet de tester l’envoi d’un mauvais type dans un POST
  - Vérifie que l’application retourne bien une erreur si le type est invalide

---

## Part 2 : Tests E2E (End-to-End)

- Test simple sur la route `/get`
- Permet de vérifier que l’application fonctionne correctement dans son ensemble

---

## Part 3 : Tests d’intégration

- Test du service `dice type`
- Permet de vérifier que le service fonctionne correctement avec ses dépendances
- Vérifie le bon comportement global du module `dice-type`
