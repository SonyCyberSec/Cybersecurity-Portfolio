# 📘 Lesson 02 – Operating System (Summary)

This lesson explains what an operating system is, how it works internally, and why its architecture and features are essential for cybersecurity and system performance.

<details>
<summary>🔹 What an Operating System Does</summary>

An OS is the core software that:  

- Manages hardware resources  
- Runs applications  
- Allocates memory  
- Handles processes  
- Controls devices and files  
- Provides security and access control  

It acts as the bridge between users, applications, and hardware.

</details>

<details>
<summary>🔹 OS Architecture</summary>

The OS follows a layered structure consisting of:  

1. **Applications** – programs users interact with  
2. **APIs** – allow apps to request OS services  
3. **System Calls** – privileged operations performed by the OS  
4. **Drivers** – help the OS communicate with hardware  
5. **HAL (Hardware Abstraction Layer)** – keeps hardware interactions consistent  
6. **Hardware** – CPU, memory, disk, devices  

**Example:**  
When you open a file in Notepad, the layers work together:  
`APIs → System Calls → Drivers → HAL → Hardware`  

</details>

<details>
<summary>🔹 Key OS Features</summary>

- **Device Management:** OS installs and manages drivers  
- **GUI:** Interface like taskbar, icons  
- **File System Management:** Organizes storage, sets permissions  
- **Security & Access Control:** Authentication, authorization  
- **Process Management:** Handles program execution & multitasking  
- **Memory Management:** Allocates RAM, manages active processes  

</details>

<details>
<summary>🔹 Virtual Memory</summary>

Virtual memory allows the OS to use part of the hard drive as extra RAM.  

**Key concepts:**  

- **Virtual vs. Physical Memory**  
  - Virtual = flexible, uses disk, slower  
  - Physical = RAM, faster, limited  

- **Paging vs. Segmentation**  
  - Paging → fixed-size blocks  
  - Segmentation → variable-sized blocks  

- **MMU (Memory Management Unit)** performs address translation  

Virtual memory improves multitasking and application performance.

</details>

<details>
<summary>🔹 Why This Matters in Cybersecurity</summary>

Understanding OS internals helps with:  

- Memory analysis  
- Process monitoring  
- System hardening  
- Malware detection  
- Investigating system calls & driver behavior  

</details>

<details>
<summary>✔ Key Takeaways</summary>

- The OS enables communication between software and hardware.  
- Drivers, HAL, and system calls are essential components of OS operation.  
- Virtual memory improves performance and security through isolation.  
- OS features such as process, memory, and file management are critical for secure system operation.

</details>
