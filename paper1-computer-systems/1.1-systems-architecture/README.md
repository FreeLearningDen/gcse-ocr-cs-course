# 1.1 Systems Architecture
Placeholder content for this topic.

# 🖥️ 1.1.1 Architecture of the CPU (OCR GCSE Computer Science - J277)

## 📌 Purpose of the CPU
The **Central Processing Unit (CPU)** is the brain of the computer. It is responsible for:
- Executing program instructions
- Performing arithmetic and logic operations
- Managing the flow of data within the system

---

## 🔄 The Fetch-Execute Cycle

### 1. Fetch
- The **Program Counter (PC)** holds the address of the next instruction.
- This address is copied into the **Memory Address Register (MAR)**.
- The instruction is fetched from RAM and loaded into the **Memory Data Register (MDR)**.
- The **PC** is incremented to point to the next instruction.

### 2. Decode
- The **Control Unit (CU)** decodes the instruction in the MDR.
- The CU determines the required operation.

### 3. Execute
- The instruction is executed:
  - The **ALU** performs calculations or logic operations.
  - Data may be stored or retrieved from memory.
  - The result may be stored in the **Accumulator**.

---

## 🧩 Common CPU Components

| Component      | Description |
|----------------|-------------|
| **ALU** (Arithmetic Logic Unit) | Performs arithmetic and logic operations |
| **CU** (Control Unit) | Decodes instructions and coordinates actions of the CPU |
| **Cache** | High-speed memory storing frequently used data/instructions |
| **Registers** | Small, fast memory locations inside the CPU |

---

## 🏛️ Von Neumann Architecture Registers

| Register | Role |
|----------|------|
| **MAR** (Memory Address Register) | Stores the address of the next instruction/data to fetch |
| **MDR** (Memory Data Register) | Stores the data fetched from or to be written to memory |
| **PC** (Program Counter) | Stores the memory address of the next instruction |
| **Accumulator** | Stores results from the ALU |

---

## ⚖️ Storing Data vs Storing Addresses

| Concept | Description | Example |
|--------|-------------|---------|
| **Data** | Actual values used in operations | `5`, `"Hello"`, `1010` |
| **Address** | Memory location where data is stored | `0x004F`, memory cell address |

> 🧠 **MAR** stores addresses.  
> 🧠 **MDR**, **ALU**, and **Accumulator** handle data.

---

## ✅ Required Knowledge
- Actions at each stage of the fetch-execute cycle
- Role/purpose of each CPU component
- What each register stores (data or address)
- Difference between storing data and storing an address

## ❌ Not Required
- Detailed knowledge of how data moves between registers during each stage

---

📎 **Need More?**  
Want this as a [PowerPoint presentation](https://github.com/gcse-ocr-cs-course/paper1-computer-systems/1.1-systems-architecture/slide), [worksheet](https://github.com/your-repo/worksheets), or [YouTube script](https://github.com/your-repo/videos)? Let me know!
