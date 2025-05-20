

---

## 📘 Sets and Functions

### 🟦 Sets

- **Definition**: A _set_ is a well-defined collection of distinct elements.
    
- Notation: A={1,2,3}A = \{1, 2, 3\}
    

#### Operations on Sets

- **Union**:$A \cup B$
    
- **Intersection**: $A \cap B$
    
- **Set Difference**: A - B$
    
- **Complement**: $A^c$
    
- **Power Set**: $\mathcal{P}(A)$
    
- **Cartesian Product**: $A \times B$
    

#### Algebras of Sets

- **Distributive Laws**:
    
$$A \cap (B \cup C) = (A \cap B) \cup (A \cap C) $$
$$A \cup (B \cap C) = (A \cup B) \cap (A \cup C)$$

---

### 🔢 Set of Numbers

- [[Natural Numbers]]$$\mathbb{N}: Natural numbers$$
    
- [[Integers]]$$\mathbb{Z}: Integers$$
    
- [[Rational numbers]]$$\mathbb{Q}: Rational numbers$$
    
- [[Real numbers]]$$\mathbb{R}: Real numbers$$
    
- [[Rational numbers]]$$\mathbb{C}: Complex numbers$$
    

---

## 🔁 Relations

### Properties of Relations

Given a relation R on set A:

- **Reflexive**:  $\forall a \in A,\, (a, a) \in R$
    
- **Symmetric**: $(a, b) \in R \Rightarrow (b, a) \in R$
    
- **Transitive**: $(a, b), (b, c) \in R \Rightarrow (a, c) \in R$
[[Relation Sets]]
[[Binary Relation]]

### Equivalence Relations

- A relation is an **equivalence relation** if it is **reflexive**, **symmetric**, and **transitive**.
    

### Partitions

- A **partition** of a set AA is a collection of non-empty, disjoint subsets {Ai}\{A_i\} such that:
    
    $$\bigcup A_i = A, \quad A_i \cap A_j = \emptyset \text{ for } i \ne j$$

---

## 🧮 Functions

- **Definition**: A function $f: A \to B$ assigns each element in $A$ to one element in $B$.
    

### Types of Functions

- **Injection (One-to-one)**: $f(a_1) = f(a_2) \Rightarrow a_1 = a_2$
    
- **Surjection (Onto)**: $\forall b \in B,\, \exists a \in A: f(a) = b$
    
- **Bijection**: Both injective and surjective
    
- **Inverse Function**: If $f$ is bijective, then $f^{-1}(b) = a$
    

### Composite Function

- If $f: A \to B and g:B→Cg: B \to C$, then:
    
	$$(g \circ f)(x) = g(f(x))$$

---

## 🗄️ Databases

### Functional Dependence

- $A \to B$: Attribute $B$ is **functionally dependent** on attribute $A$
    
- Example: If student ID determines name, then:
    $$\text{StudentID} \to \text{Name}$$

### Normal Forms

- **1NF (First Normal Form)**: Atomic values only (no repeating groups)
    
- **2NF**: 1NF + no partial dependency
    
- **3NF**: 2NF + no transitive dependency
    
- **BCNF**: Every determinant is a candidate key
    

---

Let me know if you’d like this note split into multiple files or enhanced with diagrams or flashcards (e.g., using Obsidian's **dataview**, **canvas**, or **Anki plugin**).