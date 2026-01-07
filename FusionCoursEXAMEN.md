# 📘 ÉLECTRONIQUE NUMÉRIQUE – S1

## **Support de cours complet avec méthodes, rappels et corrigés types**

🎯 **Objectif pédagogique**

* Comprendre les bases **sans stress**
* Savoir **analyser un sujet d’examen**
* Apprendre à **raisonner pas à pas**
* Gagner des points même en cas de doute

---

## 🧩 CHAPITRE 1 – RAPPELS FONDAMENTAUX

### 1.1 Qu’est-ce que l’électronique numérique ?

L’électronique numérique étudie les **circuits logiques** qui fonctionnent avec **deux niveaux** :

* **0** → Faux / OFF / 0V
* **1** → Vrai / ON / 5V ou 3.3V

👉 Contrairement à l’électronique analogique, on ne travaille **pas avec des valeurs continues**, mais uniquement **0 ou 1**.

---

### 1.2 Types de circuits numériques

| Type                 | Définition                                               |
| -------------------- | -------------------------------------------------------- |
| Circuit combinatoire | La sortie dépend **uniquement des entrées instantanées** |
| Circuit séquentiel   | La sortie dépend des entrées **et de la mémoire**        |

📌 **Dans cet examen : uniquement COMBINATOIRE**

---

## 🧩 CHAPITRE 2 – PORTES LOGIQUES (BASE DU COURS)

### 2.1 Porte NON (NOT)

| a | ¬a |
| - | -- |
| 0 | 1  |
| 1 | 0  |

📌 Inverse la valeur

---

### 2.2 Porte ET (AND)

| a | b | a · b |
| - | - | ----- |
| 0 | 0 | 0     |
| 0 | 1 | 0     |
| 1 | 0 | 0     |
| 1 | 1 | 1     |

📌 Sortie à 1 **seulement si tout est à 1**

---

### 2.3 Porte OU (OR)

| a | b | a + b |
| - | - | ----- |
| 0 | 0 | 0     |
| 0 | 1 | 1     |
| 1 | 0 | 1     |
| 1 | 1 | 1     |

📌 Sortie à 1 si **au moins une entrée vaut 1**

---

## 🧩 CHAPITRE 3 – ANALYSE D’UN SCHÉMA LOGIQUE (EXAMEN)

### 3.1 Méthode obligatoire (clé de la réussite)

👉 **Ne jamais écrire la fonction finale directement**

#### Étape 1 : Identifier les entrées

* a, b, c

#### Étape 2 : Nommer les sorties intermédiaires

Exemple :

* X = ¬a
* Y = X + b
* Z = a + c

#### Étape 3 : Écrire la fonction finale

[
F = (¬a + b)·(a + c)
]

📌 **Cette méthode seule peut donner 6 à 8 points**

---

## 🧩 CHAPITRE 4 – TABLE DE VÉRITÉ (PARTIE LA PLUS NOTÉE)

### 4.1 Règle essentielle

[
\text{Nombre de lignes} = 2^n
]

* 1 entrée → 2 lignes
* 2 entrées → 4 lignes
* 3 entrées → 8 lignes

---

### 4.2 Construction pas à pas

| a | b | c | ¬a | (¬a+b) | (a+c) | F |
| - | - | - | -- | ------ | ----- | - |
| 0 | 0 | 0 | 1  | 1      | 0     | 0 |
| 0 | 0 | 1 | 1  | 1      | 1     | 1 |
| 0 | 1 | 0 | 1  | 1      | 0     | 0 |
| 0 | 1 | 1 | 1  | 1      | 1     | 1 |
| 1 | 0 | 0 | 0  | 0      | 1     | 0 |
| 1 | 0 | 1 | 0  | 0      | 1     | 0 |
| 1 | 1 | 0 | 0  | 1      | 1     | 1 |
| 1 | 1 | 1 | 0  | 1      | 1     | 1 |

📌 **Toujours ajouter les colonnes intermédiaires**

---

## 🧩 CHAPITRE 5 – MULTIPLEXEUR (MUX)

### 5.1 Définition

Un multiplexeur est un **sélecteur de données** :

* Plusieurs entrées
* Une seule sortie
* Des lignes de sélection

---

### 5.2 Exemple : MUX 8 → 1

* Entrées : E0 à E7
* Sélections : S2, S1, S0

[
\text{Sortie} = E_{(S2S1S0)}
]

---

### 5.3 Table de fonctionnement

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

📌 Astuce examen : écrire ce tableau **avant toute réponse**

---

## 🧩 CHAPITRE 6 – QUESTIONS DE COURS (VRAI / FAUX)

### Exemple 1

❓ *Un circuit combinatoire possède une mémoire*
❌ FAUX
✔️ Justification :

> Il ne dépend que des entrées instantanées.

---

### Exemple 2

❓ *Un multiplexeur est un circuit combinatoire*
✅ VRAI
✔️ Justification :

> Sa sortie dépend uniquement des entrées et sélections.

---

## 🧩 CHAPITRE 7 – ERREURS QUI FONT PERDRE DES POINTS

❌ Aller trop vite
❌ Ne pas écrire les étapes
❌ Oublier les tables intermédiaires
❌ Répondre sans justification

---

## 🧩 CHAPITRE 8 – MÉTHODE EXAMEN (STRATÉGIE 14+/20)

1. Lire calmement le sujet
2. Identifier entrées / sorties
3. Nommer chaque signal
4. Construire les tables
5. Soigner la présentation
6. Écrire même en cas de doute

---

## ✅ CONCLUSION MOTIVANTE

> Tu peux rater une réponse,
> mais **tu ne dois jamais rater la méthode**.

Avec ce support :

* tu sais **quoi faire**
* tu sais **quoi écrire**
* tu peux **réussir le rattrapage**

---

📌 **Prochaine étape possible (au choix)** :

* Sujet blanc corrigé comme à l’examen
* Fiche résumé 2 pages
* Exercices progressifs niveau débutant → examen

Dis-moi ce que tu veux 👌
