

---

## 🏗️ Code Compiling: Step-by-Step Process

When you write code in a compiled language (like **C, C++, or Rust**), it goes through several stages before becoming an executable program.

---

### 🧾 1. **[[Preprocessing]]** 🔍

(Only in some languages like C/C++)

* 🔧 Handles **directives** like `#include`, `#define`, `#ifdef`
* 🧹 Removes comments, expands macros
* 📄 Output: Cleaned-up source code

---

### 👨‍🏭 2. **[[Compilation]]** 🧠

* Converts the **cleaned source code** into **assembly code**

* Performs:

  * 🧠 **Syntax analysis**
  * 🧮 **Semantic analysis**
  * 💡 **Optimization**

* 📄 Output: Assembly code (`.s` or similar)

---

### 🛠️ 3. **[[Assembly]]** 🧩

* Translates the **assembly code** into **machine code** (binary instructions)
* Output: **Object file** (`.o` or `.obj`)

---

### 🔗 4. **[[Linking]]** 🔗

* Combines:

  * Multiple **object files**
  * 📚 Required **libraries** (e.g., `math.h`)

* Resolves external references (e.g., function calls)

* 🧱 Output: A **single executable file** (like `.exe` or ELF binary)

---

### 🏁 Final Result

✅ Ready-to-run **binary executable**
➡️ Can be run on the target system **without** needing the original source code.

---

### 📦 Example: Compiling a C Program

```c
// hello.c
#include <stdio.h>

int main() {
    printf("Hello, world!\n");
    return 0;
}
```

**GCC Compilation Process**:

```bash
gcc hello.c -o hello
```

Under the hood:

1. `Preprocessor`: Expands `#include <stdio.h>`
2. `Compiler`: Translates C to assembly
3. `Assembler`: Produces object file (`hello.o`)
4. `Linker`: Links with standard C library ➡️ `hello`

---

Let me know if you'd like a **diagram**, **flowchart**, or **visual map** for this process!
