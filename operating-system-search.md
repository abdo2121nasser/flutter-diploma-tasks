# 🖥️ Operating System — Study Notes

<br>

## 📌 What is an Operating System?

> An **Operating System (OS)** is system software that manages computer hardware and software resources, and provides common services for computer programs.

---

### 💡 Key Definition

```text
OS = The bridge between HARDWARE and the USER

Without an OS → every app would have to manage hardware directly
With an OS    → apps just call OS services, OS handles the rest
```

> At the core of every OS is the **Kernel** — the program that runs at all times and is the primary interface between hardware and software.

---

<br>

## 📌 Components of an OS

| Component | Role |
|-----------|------|
| **Kernel** | Core layer — manages CPU, memory, devices at low level |
| **Shell**  | Outer layer — handles user interaction (CLI or GUI) |

---

<br>

## 📌 Types of Operating Systems

> Modern systems come in many forms depending on their purpose:

| Type | Description | Examples |
|------|-------------|---------|
| **Batch OS** | Executes jobs in batches without user interaction | Early IBM systems |
| **Time-Sharing OS** | Rapidly switches between users/processes | UNIX, Linux |
| **Real-Time OS** | Responds within strict time limits | Aircraft systems, robotics |
| **Distributed OS** | Coordinates resources across multiple machines | Cloud systems |
| **Mobile OS** | Optimized for power efficiency and touch | Android, iOS |
| **Embedded OS** | Minimal resources for specialized devices | Arduino, smart appliances |
| **Network OS** | Manages data and users on a server | Windows Server, macOS X |

---

<br>

## 📌 Functions of an Operating System

### 1️⃣ Process Management

> A **process** is a program in execution. The OS decides which process runs, when, and for how long.

```text
Key concepts:
  - Multitasking    → multiple processes share the CPU
  - Time-sharing    → CPU switches between processes rapidly
  - Thread          → a lightweight unit of a process
  - Scheduling      → OS decides process execution order
```

---

### 2️⃣ Memory Management

> The OS controls how RAM is allocated, protected, and shared between processes.

```text
Key concepts:
  - Allocation        → assign memory blocks to processes
  - Deallocation      → free memory when a process ends
  - Virtual Memory    → use disk as extra RAM when RAM is full
  - Paging            → divide memory into fixed-size "pages"
  - Segmentation      → divide memory into variable-size "segments"
  - Fragmentation     → wasted memory gaps (internal / external)
  - Swapping          → move idle processes to disk to free RAM
```

```
Example — Paging:
  RAM is divided into FRAMES  (fixed size)
  Process is divided into PAGES (same fixed size)
  A Page Table maps each page → its frame in RAM
```

---

### 3️⃣ File System Management

> The OS handles how files are stored, named, organized, and retrieved on disk.

```text
Key activities:
  - Create / delete files and directories
  - Read / write / move files
  - Map files onto disk storage
  - Backup and protect files
  - Manage file permissions
```

---

### 4️⃣ Device Management

> The OS controls all hardware devices through **device drivers**.

```text
Key activities:
  - Communicate with I/O devices (keyboard, disk, printer)
  - Handle interrupts from hardware
  - Assign a device driver for each device controller
  - Manage I/O operations (buffering, caching, spooling)
```

---

### 5️⃣ Security & Protection

> The OS prevents unauthorized access to data and system resources.

```text
Key mechanisms:
  - User authentication (login / password)
  - Memory protection (processes cannot access each other's memory)
  - Access control (file permissions: read / write / execute)
  - Process isolation (one buggy app cannot crash another)
```

---

<br>

## 📌 Important Concepts

### 🔹 Kernel vs User Mode

```text
Kernel Mode  →  full access to hardware, runs OS code
User Mode    →  restricted access, runs application code

System Call  →  the way user-mode programs request OS services
               e.g. open a file, allocate memory, create a process
```

---

### 🔹 Multiprogramming vs Multitasking

```text
Multiprogramming  →  multiple programs loaded in memory at once
                     CPU runs one; others wait for I/O

Multitasking      →  CPU switches between programs so fast
                     it appears they all run simultaneously
```

---

### 🔹 Virtual Memory

```text
Problem  →  RAM is limited, programs can be huge
Solution →  OS uses disk as an extension of RAM

Pages NOT in use  →  moved to disk (swap space)
Pages NEEDED      →  loaded back into RAM on demand

Result  →  programs can use more memory than physically available
```

---

### 🔹 Storage Hierarchy

```text
Fastest  →  CPU Registers
         →  Cache (L1 / L2 / L3)
         →  RAM (Main Memory)
         →  SSD / Hard Drive (Secondary Storage)
Slowest  →  Network / Cloud Storage
```

---

<br>

## 📌 Popular Operating Systems

| OS | Developer | Common Use |
|----|-----------|------------|
| **Windows** | Microsoft | Personal computing, gaming, business |
| **macOS** | Apple | Creative industries, personal use |
| **Linux** | Open-source (Linus Torvalds) | Servers, programming, supercomputers |
| **Android** | Google (based on Linux) | Mobile devices |
| **iOS** | Apple | iPhones and iPads |
| **UNIX** | AT&T Bell Labs | Large systems, the ancestor of Linux |

> As of 2025, **Android** is the most popular OS worldwide with ~38% market share, followed by **Windows** at ~33%.

---

<br>

## 📌 Quick Summary

```text
Operating System = Manager of your entire computer

It manages:
  ✅ CPU         → Process Management
  ✅ RAM         → Memory Management
  ✅ Disk        → File System Management
  ✅ Devices     → Device Management
  ✅ Data        → Security & Protection
```

---
