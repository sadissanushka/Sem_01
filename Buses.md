Here’s a complete and clear **Obsidian note** on **Buses**, formatted with **emojis** and structured for your **IN1321 – Computer Organization** course:

---

## 🚌 Buses

📚 _IN1321 – Computer Organization_

---

### 🔍 Definition

A **bus** is a communication system that **transfers data** between components inside a computer or between computers. It is a shared pathway through which data and signals travel.

> 🧠 Think of a bus like a set of wires or tracks connecting various parts of the computer to allow data to flow between them.

---

### 🧩 Types of Buses

#### 📤 1. **Data Bus**

- 🚚 Transfers **actual data** between CPU, memory, and I/O.
    
- 🔢 Width (e.g., 8-bit, 16-bit, 32-bit, 64-bit) determines how much data is transferred at once.
    
- 🧠 Bi-directional (data can go both ways).
    

#### 📁 2. **Address Bus**

- 🧭 Carries the **address of memory** or I/O location.
    
- 🧵 Unidirectional (CPU → Memory/I/O).
    
- 🧠 Width determines **maximum addressable memory**.
    
    - e.g., 16-bit address bus → 2¹⁶ = 65,536 memory locations.
        

#### 🕹️ 3. **Control Bus**

- 🎮 Carries **control signals** (read/write, interrupt, clock, etc.).
    
- 🔄 Used to manage and coordinate operations.
    
- Includes signals like:
    
    - 📥 **Read**
        
    - 📤 **Write**
        
    - 🛑 **Interrupt request (IRQ)**
        
    - ⏱️ **Clock signals**
        

---

### 🔌 System Bus = Data + Address + Control

🧷 The **System Bus** is a combination of all three buses and connects the CPU with **main memory** and **I/O devices**.

---

### 🖼️ Simple Diagram (Text Style)

```
       +--------+       +--------+       +--------+
       |  CPU   |<----->| Memory |<----->|  I/O   |
       +--------+       +--------+       +--------+
           ↑                ↑                ↑
      Address/Data/Control Buses (Shared Path)
```
![[Pasted image 20250603113741.jpg]]
---

### 🆚 Parallel vs Serial Buses

|Feature|Parallel Bus 🛤️|Serial Bus 🔗|
|---|---|---|
|Data Transfer|Multiple bits at once|One bit at a time|
|Speed|Faster over short distances|Better for longer distances|
|Example|Internal system bus|USB, SATA, PCIe|

---

### 📝 Notes

```markdown
- [ ] Understand how bus width affects system performance
- [ ] Draw diagram showing how CPU connects to memory via buses
- [ ] Learn difference between internal & external buses
```

---

Would you like a **memory-map diagram** or a **summary flashcard format** for quick review?