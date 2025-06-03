Here’s a clear and visually enhanced **Obsidian note** on **Computer Start-Up (Booting Process)** for your **IN1321 – Computer Organization** course, complete with emojis:

---

## ⚡ Computer Start-Up (Booting Process)

📚 _IN1321 – Computer Organization_

---

### 🔍 What is Booting?

**Booting** is the process of **starting a computer** from a powered-off state and **loading the operating system (OS)** into RAM so the system becomes usable.

---

### 🧭 Types of Booting

- 🔄 **Cold Boot** (Hard Boot): Starting the computer from power off
    
- 🔁 **Warm Boot** (Soft Boot): Restarting the computer without turning off power (e.g., Ctrl + Alt + Del)
    

---

### 🧩 Steps in the Booting Process

#### 1️⃣ **Power On**

- ⚡ Power is applied to the motherboard and components.
    
- 💡 Power Supply Unit (PSU) initiates power to CPU and RAM.
    

#### 2️⃣ **POST (Power-On Self-Test)**

- 🧪 BIOS/UEFI runs diagnostic checks on hardware (RAM, keyboard, drives).
    
- ✅ If successful, the system continues booting.
    
- ❌ If failure, it halts with **beep codes** or error messages.
    

#### 3️⃣ **BIOS/UEFI Execution**

- 📕 BIOS (Basic Input Output System) or UEFI is stored in **ROM**.
    
- 🔍 Searches for bootable device (HDD/SSD, USB, CD).
    

#### 4️⃣ **Bootloader Execution**

- 🚀 BIOS/UEFI loads the **bootloader** (e.g., GRUB, Windows Boot Manager) from the bootable storage.
    
- 📍 Located in **MBR** (Master Boot Record) or **GPT** (GUID Partition Table).
    

#### 5️⃣ **Operating System Loading**

- 🧠 Bootloader loads OS kernel into **RAM**.
    
- 📂 OS initializes system drivers, services, and user interface.
    

#### 6️⃣ **System Ready**

- 👨‍💻 User sees login screen or desktop and can start using the computer.
    

---

### 📊 Visual Flow Summary

```
Power On
   ↓
POST (Check hardware)
   ↓
BIOS/UEFI (in ROM)
   ↓
Bootloader (MBR/GPT)
   ↓
Load OS Kernel into RAM
   ↓
Initialize Drivers & Services
   ↓
User Interface (Ready to use)
```

---

### 📚 Important Terms

- **BIOS/UEFI**: Firmware stored in ROM that starts the computer.
    
- **POST**: Hardware test during boot.
    
- **Bootloader**: Small program that loads the OS.
    
- **Kernel**: Core part of the OS, loaded into RAM.
    
- **MBR/GPT**: Disk partition structures where boot info is stored.
    

---

### 📝 Notes

```markdown
- [ ] Draw full boot process diagram
- [ ] Understand the role of ROM, RAM, BIOS, Bootloader
- [ ] Compare BIOS vs UEFI
```

---

Would you like a **flowchart diagram** version or a **flashcard-style summary** of each boot step?