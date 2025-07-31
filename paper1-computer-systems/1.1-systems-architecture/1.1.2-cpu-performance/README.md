# 1.1.2 CPU Performance (OCR GCSE Computer Science - J277)

## How Common Characteristics of CPUs Affect Performance

### 🕒 Clock Speed
Clock speed is the number of cycles the CPU performs per second, measured in **GHz** (1 GHz = 1 billion cycles/second).  
A higher clock speed means the CPU can execute more instructions per second.

**Effect**:  
- Faster execution of instructions  
- Increased heat and power consumption  

**Example**: 3.5 GHz CPU is faster than a 2.0 GHz CPU (if other specs are equal)

---

### 🧠 Cache Size
Cache is a small, high-speed memory located in or near the CPU that stores frequently accessed data and instructions.

**Effect**:  
- Faster access to commonly used data  
- Reduces reliance on slower RAM  

**Cache Levels**:  
- **L1**: Smallest, fastest  
- **L2**: Larger, slower  
- **L3**: Largest, slowest (but still faster than RAM)

---

### 🧩 Number of Cores
Each core is an independent processing unit capable of executing tasks. Multi-core CPUs can perform tasks in parallel.

**Effect**:  
- Better multitasking and parallel processing  
- Software must be designed to take advantage of multiple cores

**Example**: A quad-core processor can handle four tasks at once.

---

## Combined Effects on Performance

| Characteristic  | Individual Effect                  | Combined Effect                                                   |
|----------------|-------------------------------------|-------------------------------------------------------------------|
| Clock Speed     | Faster instruction processing       | May be limited by slow memory or low core count                   |
| Cache Size      | Quicker data access                 | Enhances performance when combined with higher clock speed        |
| Number of Cores | More tasks handled simultaneously   | Best used with multi-threaded software and sufficient cache       |

---

## Summary

| Characteristic   | Increases Performance by                           |
|------------------|----------------------------------------------------|
| Clock Speed      | Executing more instructions per second             |
| Cache Size       | Providing faster access to frequently used data    |
| Number of Cores  | Running multiple tasks in parallel                 |

---

*For use in GCSE Computer Science, Unit 1.1.2*
