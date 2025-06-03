## 🔗 Binary Relation

### 📌 Definition

A **binary relation** $R$ from a set $A$ to a set $B$ is a subset of the Cartesian product:

$$
R \subseteq A \times B
$$

If $(a, b) \in R$, we say “$a$ is related to $b$” and write:

$$
a \mathrel{R} b
$$

When $A = B$, we say that $R$ is a **relation on $A$**.

---

### 🧮 Examples

* Less than: $R = \{ (a, b) \in \mathbb{N} \times \mathbb{N} \mid a < b \}$
* Divides: $R = \{ (a, b) \in \mathbb{N} \times \mathbb{N} \mid a \mid b \}$

---

### 🔍 Properties of Binary Relations (on set $A$)
Homogeneous

1. **[[Reflexive]]**
- Definition:
A reflexive relation on a set is a relation where every element is related to itself.
-In formal terms:
A relation R on a set A is reflexive if for every element a in A, the pair (a, a) is in R.

   $$
   \forall a \in A,\quad (a, a) \in R
   $$

3. **[[Symmetric]]**
   $$
   \forall a, b \in A,\quad (a, b) \in R \Rightarrow (b, a) \in R
   $$

4. **[[Antisymmetric]]**

   $$
   \forall a, b \in A,\quad (a, b) \in R \land (b, a) \in R \Rightarrow a = b
   $$

5. **[[Transitive]]**

   $$
   \forall a, b, c \in A,\quad (a, b) \in R \land (b, c) \in R \Rightarrow (a, c) \in R
   $$

---
[[Combining relations]]
[[Composition of relation]]
---
### 🧩 Special Types of Relations

* **Equivalence Relation**: Reflexive, symmetric, and transitive
  → Forms **partitions** of the set.

* **Partial Order**: Reflexive, antisymmetric, and transitive
  → Defines a **partially ordered set (poset)**.

---

### 📈 Representation

* **As a Set**: $R = \{(a, b), (b, c), \ldots\}$
* **As a Matrix** (for finite sets)
* **As a Digraph**: Nodes with directed edges

---

Let me know if you’d like this extended with **examples**, **visuals**, or **practice problems**.
