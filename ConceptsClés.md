# 📘 ÉLECTRONIQUE NUMÉRIQUE – TOP 50 CONCEPTS CLÉS

🎯 *Objectif : passer de 8/20 à ≥14/20*

---

## 🧩 A. BASES FONDAMENTALES (1 → 10)

### 1. Système binaire

**Définition** : système à deux états (0 et 1).
**Exemple** : interrupteur ON/OFF.
**Nuance** : 1 ≠ toujours 5V (peut être 3.3V).

---

### 2. Niveau logique

**Définition** : valeur électrique représentant 0 ou 1.
**Exemple** : 0V → 0, 5V → 1.
**Nuance** : zones de tolérance (pas strict).

---

### 3. Signal numérique

**Définition** : signal discret (0 ou 1).
**Exemple** : sortie d’une porte logique.
**Nuance** : sensible au bruit si mal filtré.

---

### 4. Circuit numérique

**Définition** : circuit traitant des signaux binaires.
**Exemple** : calculatrice.
**Nuance** : numérique ≠ informatique.

---

### 5. Circuit combinatoire

**Définition** : sortie dépend uniquement des entrées.
**Exemple** : additionneur, multiplexeur.
**Nuance** : aucune mémoire.

---

### 6. Circuit séquentiel

**Définition** : sortie dépend du passé.
**Exemple** : compteur.
**Nuance** : contient une mémoire (bascule).

---

### 7. Fonction logique

**Définition** : relation mathématique entre entrées et sortie.
**Exemple** : F = a·b.
**Nuance** : doit correspondre exactement au schéma.

---

### 8. Variable logique

**Définition** : symbole représentant une entrée.
**Exemple** : a, b, c.
**Nuance** : une variable = un fil.

---

### 9. Complément logique

**Définition** : inversion d’une variable.
**Exemple** : ¬a.
**Nuance** : une seule inversion change toute la table.

---

### 10. Algèbre de Boole

**Définition** : mathématiques du logique.
**Exemple** : a + a = a.
**Nuance** : ≠ algèbre classique.

---

## 🧩 B. PORTES LOGIQUES (11 → 20)

### 11. Porte NON (NOT)

**Exemple** : ¬a.
**Nuance** : inverse toujours, sans condition.

---

### 12. Porte ET (AND)

**Exemple** : a·b.
**Nuance** : sensible aux zéros.

---

### 13. Porte OU (OR)

**Exemple** : a + b.
**Nuance** : 1 suffit.

---

### 14. Porte NAND

**Exemple** : ¬(a·b).
**Nuance** : universelle.

---

### 15. Porte NOR

**Exemple** : ¬(a + b).
**Nuance** : universelle aussi.

---

### 16. Porte XOR

**Exemple** : a ⊕ b.
**Nuance** : 1 si différent.

---

### 17. Porte XNOR

**Exemple** : ¬(a ⊕ b).
**Nuance** : 1 si identique.

---

### 18. Symbole logique

**Exemple** : IEC / ANSI.
**Nuance** : formes différentes, même fonction.

---

### 19. Porte universelle

**Définition** : permet de créer toutes les autres.
**Exemple** : NAND.
**Nuance** : très utilisée en pratique.

---

### 20. Fan-in / Fan-out

**Définition** : nombre d’entrées / sorties supportées.
**Nuance** : limite physique réelle.

---

## 🧩 C. TABLES & ANALYSE (21 → 30)

### 21. Table de vérité

**Définition** : liste toutes les combinaisons.
**Exemple** : 3 entrées → 8 lignes.
**Nuance** : outil le plus noté.

---

### 22. Nombre de lignes

**Formule** : 2ⁿ.
**Nuance** : erreur fréquente à l’examen.

---

### 23. Colonnes intermédiaires

**Définition** : calculs partiels.
**Nuance** : donnent des points même si F est faux.

---

### 24. Analyse de schéma

**Méthode** : découper par blocs.
**Nuance** : ne jamais lire globalement.

---

### 25. Simplification logique

**Définition** : réduire une fonction.
**Exemple** : a + a·b = a.
**Nuance** : pas toujours demandée.

---

### 26. Forme canonique

**Définition** : somme de minterms.
**Nuance** : très formelle, très notée.

---

### 27. Minterm

**Définition** : produit logique unique.
**Exemple** : a·b·c.
**Nuance** : lié à une ligne = 1.

---

### 28. Maxterm

**Définition** : somme logique.
**Nuance** : lié à une ligne = 0.

---

### 29. Karnaugh (K-map)

**Définition** : outil graphique de simplification.
**Nuance** : éviter les erreurs de groupement.

---

### 30. Redondance logique

**Définition** : parties inutiles.
**Nuance** : simplification = coût réduit.

---

## 🧩 D. FONCTIONS ET CIRCUITS (31 → 40)

### 31. Multiplexeur (MUX)

**Définition** : sélectionneur.
**Exemple** : 8→1.
**Nuance** : très fréquent à l’examen.

---

### 32. Démultiplexeur (DEMUX)

**Définition** : inverse du MUX.
**Nuance** : attention à la confusion.

---

### 33. Décodeur

**Définition** : n→2ⁿ.
**Exemple** : 3→8.
**Nuance** : une seule sortie active.

---

### 34. Encodeur

**Définition** : inverse du décodeur.
**Nuance** : ambigu sans priorité.

---

### 35. Additionneur

**Définition** : addition binaire.
**Exemple** : demi-additionneur.
**Nuance** : XOR + AND.

---

### 36. Comparateur

**Définition** : compare deux nombres.
**Nuance** : logique conditionnelle.

---

### 37. Priorité logique

**Définition** : ordre d’importance.
**Nuance** : souvent implicite.

---

### 38. Enable

**Définition** : autorisation de fonctionnement.
**Nuance** : sortie forcée si désactivé.

---

### 39. Signal actif

**Définition** : actif à 0 ou 1.
**Nuance** : attention au petit rond (○).

---

### 40. Bruit logique

**Définition** : perturbation.
**Nuance** : cause d’erreurs réelles.

---

## 🧩 E. EXAMEN & PIÈGES (41 → 50)

### 41. Justification

**Définition** : explication écrite.
**Nuance** : obligatoire pour V/F.

---

### 42. Présentation

**Nuance** : points faciles.

---

### 43. Méthode

**Nuance** : plus importante que le résultat.

---

### 44. Erreur de lecture

**Nuance** : cause n°1 des 8/20.

---

### 45. Confusion entrée/sortie

**Nuance** : très pénalisée.

---

### 46. Symboles inversés

**Nuance** : attention aux bulles.

---

### 47. Hypothèses non écrites

**Nuance** : écrire ce que tu supposes.

---

### 48. Gestion du temps

**Nuance** : commencer par le sûr.

---

### 49. Réponse partielle

**Nuance** : vaut mieux que rien.

---

### 50. Confiance

**Nuance** : la panique fait perdre des points.

---

## ✅ CONCLUSION

👉 **Maîtriser ces 50 concepts = réussir l’examen**
👉 Pas besoin d’être fort en maths
👉 Juste **méthode + compréhension**

Si tu veux :

* 📄 une **fiche PDF 5 pages**
* 📝 des **exercices corrigés pour chaque concept**
* 🎓 un **plan de révision personnalisé**

Dis-moi 👍
