
### 🔣 Symbols
$\forall$ *For All*
$\exists$ *There Exists*
$\Rightarrow$ *implies 'implies to net Statement'*
$\Leftrightarrow$ *If and Only*

---

## 📘 Sets and Functions


### 🔢 Set of Numbers
$$\mathbb{N} \subset \mathbb{Z} \subset\mathbb{Q} \subset\mathbb{R} \subset\mathbb{C}$$

- [[Natural Numbers]]$$\mathbb{N}: Natural numbers$$
    
- [[Integers]]$$\mathbb{Z}: Integers$$
    
- [[Rational numbers]]$$\mathbb{Q}: Rational numbers$$
    
- [[Real numbers]]$$\mathbb{R}: Real numbers$$
    
- [[Rational numbers]]$$\mathbb{C}: Complex numbers$$
---

### 🟦 Sets

- **Definition**: A _set_ is a well-defined collection of distinct elements(Obj).
	$B = \emptyset$ *Empty set*
    
- Notation: 
	$a \in S$  *"a is an element of S"*
	$a \notin S$  *"a is not an element of S"*

- Set building notation
	$A = \{1, 2, 3\}$
	$A = {x \in A, P(x)}$
	$A = \{x \text{ is satisfine} P(x)\}$
	
	

1. A set A Is a subset of B, $A \subset B$
		if $a \in A \Rightarrow a \in B$
2. Two set are equal, $A = B$
		if $A \subset B$ and $B \subset A$
3. A set A Is a **proper** subset of B, $A \subsetneq B$
		if $A \subset B$ and $A \neq B$
#### Operations on Sets

- **Union**:$A \cup B$
	$$A \cup B = \{x \mid x \in A \text{ or } x \in B\}$$

- **Intersection**: $A \cap B$
	$$A \cap B = \{x \mid x \in A \text{ and } x \in B\}$$
    
- **Set Difference**: $A - B$
	$$A - B = \{x \in A \mid  x \notin B\}$$
	
- **Complement**: $A^c$
    $$A^c = \{x : x \notin A \}$$
    
- **Power Set**: $\mathcal{P}(A)$
    
- **Cartesian Product**: $A \times B$
    
- **Disjoint**:
	 $$A \cap B = \emptyset$$
#### Algebras of Sets
**De Morgan's Laws** in set theory relate the complement of unions and intersections of sets. They are:

1. **Complement of a union**:
    
    $(A \cup B)^c = A^c \cap B^c$
    
    _The complement of the union is the intersection of the complements._
	
2. **Complement of an intersection**:
    
	$(A \cap B)^c = A^c \cup B^c$
    
    _The complement of the intersection is the union of the complements._
    


- **Distributive Laws**:
    
$$A \cap (B \cup C) = (A \cap B) \cup (A \cap C) $$
$$A \cup (B \cap C) = (A \cup B) \cap (A \cup C)$$

---


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