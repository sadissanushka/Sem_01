Here's an **Obsidian-style note** on the **Assembly** step in the compilation process, with emojis and clear formatting:

---

## ⚙️ Assembly (Step 3 of Compilation)

### 🧠 What is Assembly?

The **assembly phase** converts the **assembly code** (produced during compilation) into **machine code** (binary instructions).

🛠️ It uses an **assembler** to do this job.

---

### 🔄 Process Overview

1. 📄 **Input**:

   * Assembly code file (e.g., `program.s`)
   * Generated during the **compilation** step

2. 🔁 **Assembler Work**:

   * Converts human-readable **assembly instructions** into **object code**
   * Resolves **basic addresses** and instructions

3. 📦 **Output**:

   * Object file (e.g., `program.o`, `program.obj`)
   * Not yet executable – needs linking

---

### 🧪 Example (C Code to Assembly)

#### ✅ C Code

```c
int main() {
    return 0;
}
```

#### 🔽 Becomes Assembly Code (Example)

```asm
_main:
    mov eax, 0
    ret
```

🔧 The assembler turns this into binary format (object code).

---

### 📦 File Extensions

| File Type   | Extension      |
| ----------- | -------------- |
| Assembly    | `.s` or `.asm` |
| Object Code | `.o` or `.obj` |

---

### 💡 Fun Fact

Assembly code is **CPU architecture-specific**.
E.g., x86 assembly differs from ARM or RISC-V.

---

### 🧭 Summary

| Step        | Description                        |
| ----------- | ---------------------------------- |
| 🔡 Assembly | Translate assembly ➡️ machine code |
| 🛠️ Tool    | Assembler                          |
| 📄 Input    | `.s` file (assembly code)          |
| 📦 Output   | `.o` file (object code)            |

---

Let me know if you'd like to see how **object files** are linked into an executable next!
