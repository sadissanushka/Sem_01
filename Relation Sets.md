Here's a detailed **Obsidian note** on **Relations on Sets**, with all formulas wrapped in `$$...$$` for LaTeX block rendering:

---

## 🔗 Relation on Sets

### 📌 Definition

A **relation** RR from set AA to set BB is defined as a subset of the Cartesian product:

R⊆A×BR \subseteq A \times B

- If (a,b)∈R(a, b) \in R, we write:
    

aRba \mathrel{R} b

When A=BA = B, we say that RR is a **relation on the set AA**.

---

### 📘 Example

Let:

A={1,2,3}A = \{1, 2, 3\}

A relation RR on AA could be:

R={(1,2),(2,3),(3,1)}R = \{(1, 2), (2, 3), (3, 1)\}

---

### 🔍 Properties of Relations on a Set AA

1. **Reflexive**
    

∀a∈A,(a,a)∈R\forall a \in A,\quad (a, a) \in R

2. **Symmetric**
    

∀a,b∈A,(a,b)∈R⇒(b,a)∈R\forall a, b \in A,\quad (a, b) \in R \Rightarrow (b, a) \in R

3. **Antisymmetric**
    

∀a,b∈A,(a,b)∈R∧(b,a)∈R⇒a=b\forall a, b \in A,\quad (a, b) \in R \land (b, a) \in R \Rightarrow a = b

4. **Transitive**
    

∀a,b,c∈A,(a,b)∈R∧(b,c)∈R⇒(a,c)∈R\forall a, b, c \in A,\quad (a, b) \in R \land (b, c) \in R \Rightarrow (a, c) \in R

---

### 🔠 Types of Relations

- **Equivalence Relation**: Reflexive, Symmetric, and Transitive  
    ⇒ Partitions the set into disjoint equivalence classes.
    
- **Partial Order**: Reflexive, Antisymmetric, and Transitive  
    ⇒ Defines a partially ordered set (poset).
    

---

### 📈 Representation of Relations

1. **As a set of ordered pairs**
    

R={(a1,b1),(a2,b2),…}R = \{(a_1, b_1), (a_2, b_2), \ldots\}

2. **As a matrix** (for finite sets)
    
    - Mij=1M_{ij} = 1 if (ai,aj)∈R(a_i, a_j) \in R
        
3. **As a directed graph (digraph)**
    
    - Nodes represent elements; arrows represent related pairs.
        

---

Let me know if you'd like **examples of each type of relation**, or how to **test a relation for these properties** using code or logic!