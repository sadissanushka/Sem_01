Here’s a clean and LaTeX-supported **Obsidian note** about **Natural Numbers** with **definitions** and **key properties**. You can paste it directly into your Obsidian vault.

---

## 🔢 Natural Numbers

### 📌 Definition

The set of **natural numbers** is usually denoted by:

$$
\mathbb{N} = \{1, 2, 3, 4, 5, \ldots\}
$$

> Some definitions also include $0$, i.e., $\mathbb{N}_0 = \{0, 1, 2, 3, \ldots\}$

---

### ✅ Key Properties

1. **Well-Ordering Principle**
   Every non-empty subset of $\mathbb{N}$ has a least element.

   $$
   \forall S \subseteq \mathbb{N},\, S \ne \emptyset \Rightarrow \exists m \in S \text{ such that } \forall s \in S,\, m \le s
   $$

2. **Closure under Addition and Multiplication**

   $$
   \forall a, b \in \mathbb{N},\quad a + b \in \mathbb{N},\quad a \cdot b \in \mathbb{N}
   $$

3. **Not Closed under Subtraction and Division**

   $$
   \exists a, b \in \mathbb{N},\quad a - b \notin \mathbb{N} \quad \text{(if } a < b \text{)}
   $$

4. **Associativity**

   $$
   (a + b) + c = a + (b + c), \quad (a \cdot b) \cdot c = a \cdot (b \cdot c)
   $$

5. **Commutativity**

   $$
   a + b = b + a, \quad a \cdot b = b \cdot a
   $$

6. **Distributivity**

   $$
   a \cdot (b + c) = a \cdot b + a \cdot c
   $$

7. **Identity Elements**

   * Additive identity: $0$ (if included)
   * Multiplicative identity: $1$

8. **No Maximum Element**
   The set $\mathbb{N}$ is infinite:

   $$
   \forall n \in \mathbb{N},\quad n + 1 \in \mathbb{N}
   $$

9. **Mathematical Induction Principle**
   If:

   * $P(1)$ is true
   * $P(k) \Rightarrow P(k+1)$

   Then $P(n)$ is true for all $n \in \mathbb{N}$

---

Let me know if you want visual aids like number lines or induction examples included in the note!
