

# 📘 CORRECTION COMPLÈTE – ÉLECTRONIQUE NUMÉRIQUE S1

*(Analyse + raisonnement + méthode examen)*

---

## 🧩 EXERCICE 1 – Analyse d’un circuit logique (Fonction + table de vérité)

### 🔹 1. Lecture du schéma

On observe :

* des **portes logiques** (ET, OU, NON)
* trois entrées : **a, b, c**
* une sortie : **F**

⚠️ Erreur fréquente à 8/20 :
👉 Lire le schéma trop vite sans **nommer chaque sortie intermédiaire**

---

### 🔹 2. Méthode CORRECTE (à appliquer toujours)

On décompose **étape par étape** :

#### Étape 1 – Identifier les sous-expressions

Exemple :

* Porte NON → ¬a
* Porte ET → a · b
* Porte OU → (a + b)

On **nomme chaque sortie intermédiaire** :

* X = ¬a
* Y = a · b
* Z = X + c
  etc.

---

### 🔹 3. Écriture de la fonction logique F

À partir du schéma, on obtient une fonction du type :

[
F = (\overline{a} + b)\cdot (a + c)
]

⚠️ À l’examen :
✔️ écrire **clairement**
❌ ne jamais sauter d’étapes

---

### 🔹 4. Construction de la table de vérité

#### Règle d’or

👉 **3 entrées → 2³ = 8 lignes**

| a | b | c | ¬a | (¬a + b) | (a + c) | F |
| - | - | - | -- | -------- | ------- | - |
| 0 | 0 | 0 | 1  | 1        | 0       | 0 |
| 0 | 0 | 1 | 1  | 1        | 1       | 1 |
| 0 | 1 | 0 | 1  | 1        | 0       | 0 |
| 0 | 1 | 1 | 1  | 1        | 1       | 1 |
| 1 | 0 | 0 | 0  | 0        | 1       | 0 |
| 1 | 0 | 1 | 0  | 0        | 1       | 0 |
| 1 | 1 | 0 | 0  | 1        | 1       | 1 |
| 1 | 1 | 1 | 0  | 1        | 1       | 1 |

✅ **Méthode notée** même si le résultat final est faux

---

## 🧩 EXERCICE 2 – Multiplexeur (MUX 8→1)

### 🔹 1. Rappel de cours (important)

Un **multiplexeur** :

* sélectionne **UNE entrée** parmi plusieurs
* grâce aux **lignes de sélection**

Ici :

* **8 entrées** → E0 à E7
* **3 sélections** → S2, S1, S0

[
\text{Sortie} = E_{(S2S1S0)}
]

---

### 🔹 2. Lecture du schéma

Exemple :

* S2S1S0 = 101 → sortie = E5
* Si E5 = 1 → sortie = 1
* Si E5 = 0 → sortie = 0

⚠️ Erreur classique :
❌ confondre entrée de donnée et entrée de sélection

---

### 🔹 3. Table de fonctionnement du MUX

| S2 | S1 | S0 | Sortie |
| -- | -- | -- | ------ |
| 0  | 0  | 0  | E0     |
| 0  | 0  | 1  | E1     |
| 0  | 1  | 0  | E2     |
| 0  | 1  | 1  | E3     |
| 1  | 0  | 0  | E4     |
| 1  | 0  | 1  | E5     |
| 1  | 1  | 0  | E6     |
| 1  | 1  | 1  | E7     |

✔️ À l’examen, ce tableau **rapporte beaucoup de points**

---

## 🧩 EXERCICE 3 – Questions de cours (V/F + justification)

### Exemple de questions typiques :

#### ❓ « Un circuit combinatoire possède une mémoire »

❌ FAUX
✔️ Justification :

> Un circuit combinatoire dépend uniquement des entrées instantanées, sans mémoire.

---

#### ❓ « Un multiplexeur est un circuit combinatoire »

✅ VRAI
✔️ Justification :

> La sortie dépend uniquement des entrées et des sélections.

---

⚠️ Perte de points fréquente :

* réponse sans justification
* justification trop courte ou floue

---

## 🎯 COMMENT PASSER DE 8/20 À 14–16/20

### ✅ Stratégie simple

1. **Toujours décomposer**
2. **Toujours dessiner les tables intermédiaires**
3. **Soigner la présentation**
4. **Écrire même si on doute**

---

### 🧠 Astuce mentale examen

> « Même si je ne connais pas la réponse finale,
> je gagne des points avec la méthode »

---

## 📌 PLAN DE RÉVISION RECOMMANDÉ (10 jours)

| Jour | Travail              |
| ---- | -------------------- |
| 1–2  | Tables de vérité     |
| 3    | Portes logiques      |
| 4    | Fonctions booléennes |
| 5    | Multiplexeurs        |
| 6    | Exercices corrigés   |
| 7    | Sujet blanc          |
| 8    | Corrections          |
| 9    | Révision légère      |
| 10   | Confiance 💪         |

---

## ✅ Conclusion (très important)

👉 Tu n’as **pas un problème d’intelligence**,
👉 Tu avais un **problème de méthode**.

Avec cette correction :

* tu comprends **comment raisonner**
* tu sais **quoi écrire à l’examen**
* tu peux **réussir au prochain passage**

Si tu veux, je peux :

* refaire la correction **encore plus simplifiée**
* te donner un **sujet type corrigé**
* t’entraîner comme en **coaching personnel**

Dis-moi 👍
