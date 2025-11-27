# My First OS Kernel 🖥️

A custom operating system kernel built from scratch using C++ and Assembly. This project represents an intensive 3-week deep dive into low-level systems programming, x86 architecture, and hardware interaction.

## 📖 Project Overview

Welcome to my first OS! I embarked on this project to demystify how computers work at the lowest level. Over the course of three full-time weeks (plus a week of preparation), I built a functioning kernel that can boot, manage interrupts, and handle keyboard input.

While currently "unfinished" (lacking a full file system or advanced memory paging), this repository serves as a milestone of my learning journey—from a blank text editor to printing "Hello from Kernel" on the screen.

## ⚙️ Key Features

Based on the current implementation, the OS supports:
* **Bootloader:** Custom assembly bootloader (Multiboot compliant).
* **GDT (Global Descriptor Table):** Proper memory segmentation setup.
* **IDT (Interrupt Descriptor Table):** Handling hardware and software interrupts.
* **Drivers:**
    * **Keyboard:** PS/2 keyboard driver for user input.
    * **VGA Driver:** Text mode output and cursor handling.
* **Emulation:** Configured to run on Bochs.

## 🛠️ Tech Stack

* **Languages:** C++, Assembly (x86)
* **Build Tools:** Make, GCC, LD (Linker)
* **Emulator:** Bochs (configured via `bochsrc.txt`)

## 💭 The Journey & Retrospective

> "It was a series of days of failure with bugs, mistakes in system design, and hopeless efforts... until the excitement when the modules finally pulled off and the 'Hello from Kernel' line emerged."

Building this OS was a nerve-racking but incredibly rewarding experience.

* **Timeline:** 3 weeks of full-time development (plus ~1 week of environment setup and research).
* **Challenges:** The learning curve was steep. I wrestled with setting up the cross-compiler, understanding the booting process, and debugging triple faults.
* **Future Scope:** While I am pausing development to preserve this state as a "monument" to my learning, future improvements would include Memory Management and a Virtual File System.

## 🏆 Acknowledgements & Special Thanks

This project would not have been possible without the incredible open-source community. A huge thank you to:

* **OSDev Community:** For the "Bible" of OS development materials.
* **[The Little Book about OS Development]:** For broadening my horizon on the booting process and x86 architecture.
* **Viktor Engelmann:** For his amazing video series on developing an OS from scratch.
* **Nanobyte-dev:** For guidance on setting up components and maintaining clean code.
* **Community Forums:** OSDev Forum, StackOverflow, and various legacy blogs that provided deep understanding during debugging sessions.

---
*Created with ❤️ and a lot of caffeine.*
