Here's an **Obsidian-style note** on **Preprocessing** with emojis and clear structure:

---

## 🔧 Preprocessing (Step 1 of Compilation)

### 🧠 What is Preprocessing?

The **preprocessing** step happens **before compilation**.
It prepares your source code by handling **preprocessor directives**.

🧰 Common in languages like **C/C++**

---

### ⚙️ What Does It Do?

1. 🧱 **Include Files**

   * Replaces `#include` with the contents of header files.
   * Example:

     ```c
     #include <stdio.h>
     ```

     ➡️ Gets replaced with actual code from `stdio.h`.

2. 🪄 **Macro Expansion**

   * Replaces macros defined using `#define`.
   * Example:

     ```c
     #define PI 3.14
     float area = PI * r * r;  // Becomes 3.14 * r * r
     ```

3. 🚫 **Conditional Compilation**

   * Includes or excludes parts of code based on conditions.
   * Example:

     ```c
     #ifdef DEBUG
     printf("Debug mode on\n");
     #endif
     ```

4. 🧹 **Remove Comments**

   * Strips out all comments (`//`, `/* */`) to clean the code.

---

### 🗂️ Output

The output of preprocessing is a **pure source file** without directives — ready for the **compiler**.

📄 For example:
`hello.c` ➡️ `hello.i` (preprocessed file in C)

---

### 🧪 Quick Example

#### ✅ Input (Original Code)

```c
#include <stdio.h>
#define GREETING "Hello!"
int main() {
    printf("%s\n", GREETING);
}
```

#### 🔄 After Preprocessing

```c
/* Full content of stdio.h inserted here */
int main() {
    printf("%s\n", "Hello!");
}
```

---

Let me know if you want to link this to other stages like **compilation**, **assembly**, or **linking**!
