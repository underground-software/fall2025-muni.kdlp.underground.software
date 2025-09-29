# MUNI FI Kernel Development Learning Pipeline Course Fall 2025 Information

# Course Description

Linux is the most widely used operating system in the world. The core software component of the Linux operating system is the kernel. A couple of its roles include managing hardware interactions, virtualizing system resources, and enforcing security constraints. In effect, Linux kernel powers almost all of the world’s top supercomputers, android phones, and an innumerable variety of other computers. This course will introduce students to Linux kernel development by focusing on device driver development. This will give students hands-on experience working with internal Linux kernel APIs and provide an overview of some of the core features and components of the kernel. Gaining an understanding of the inner workings of the operating system and how to make changes to it will give students an invaluable perspective on how their computers work behind the scenes that will reveal a new layer of understanding to apply to any future software engineering practice.

# Lecture Time
-   Starting Sep 15, 2025
-   Mondays 14pm-16pm CET

# Teachers
- Carlos Maiolino <cem\<at>maiolino.dev>
- Vratislav Bendel <vbendel\<at>redhat.com>
- Michal Schmidt <mschmidt\<at>redhat.com>
- Radomir Vrbovsky <rvrbovsk\<at>redhat.com>

# Lecture Room
- FI MUNI, Building S, [Room S505](https://is.muni.cz/kontakty/mistnost?lang=en;id=12880) (Fifth floor)

# Prerequisites
-   English language
-   C language knowledge
-   Basic knowledge about operating systems in general
-   Practical skills in Linux operating system (e.g. Fedora, Debian, Slackware)
-   Basic git
-   Own computer, preferably a laptop with x86 architecture

# Course enrollment
-   KDLP is taught under [PB173 Domain specific development](https://is.muni.cz/course/fi/podzim2025/PB173?lang=en)
-   The reward for passing the course is 3 credits.

# Language of Instruction
-   English

# Objectives
-   Introduce students to the Linux Kernel development workflow, show them how to create and send kernel modifications to mailing lists
-   Excite students about the wonderful world of Linux kernel community
-   Expose students to major kernel subsystems

# Syllabus
-   Introduction and development environment setup
-   General overview of core kernel concepts
-   Process management
-   Synchronization primitives
-   Memory management
-   BPF and tracing
-   Storage and filesystems
-   Networking stack
-   Device drivers
-   Kernel Debugging methods
-   GPG signing party

# Teaching Methods
-   In-person lectures
-   Homework assignments

# Assessment Methods
-   Each assignment is assigned a specific number of points based on its difficulty or importance. These points add up to a maximum of 100.
-   To pass the course, students need to accumulate at least 65 points across assignments.

# Course Schedule

| ID  | Date         | Lesson                                 | Responsible |
| --- | ------------ | -------------------------------------- | ----------- |
| 1.a | Sep 15, 2025 | [Introduction](/lectures/L01_Introduction.pdf)                           | Rado        |
| 1.b | Sep 15, 2025 | [Development environment setup](/lectures/L01_Development_Enviroment_Setup.pdf)          | Carlos      |
| 2   | Sep 22, 2025 | [Introduction to kernel structures](/lectures/L02_Basic_Intro_To_Linux_Kernel.pdf)      | Vrato       |
| 3   | Sep 29, 2025 | [Processes, syscalls, process scheduler](/lectures/L03_Process_Management.pdf) | Rado        |
| 4   | Oct 6, 2025  | Debugging 1                            | Vrato       |
| 5   | Oct 13, 2025 | Filesystems                            | Carlos      |
| 6   | Oct 20, 2025 | Memory                                 | Carlos      |
| 7   | Oct 27, 2025 | Locking                                | Carlos      |
| 8   | Nov 3, 2025  | Networking                             | Jirka       |
| 9   | Nov 10, 2025 | Device drivers                         | Michal      |
| 10  | Nov 24, 2025 | BPF                                    | Viktor      |
| 11  | Dec 1, 2025  | Debugging 2                            | Vrato       |
| 12  | Dec 8, 2025  | GPG signing party                      | Carlos      |

# Assignments

| ID | Description                                           | Max points | Due date     |
| -- | ----------------------------------------------------- | ---------- | ------------ |
| 1  | [Kernel compilation](/assignments/A01_Custom_kernel.pdf)                                    | 10         | Sep 28, 2025 |
| 2  | [Custom Syscall](/assignments/A02_Custom_Syscall.pdf)                                       | 20         | Oct 12, 2025 |


# Special Thanks

We would like to show our appreciation to the following people who have contributed to the course or without their help the course would not be existing:

- Martin Ukrop
- Joel Sawitz
- Jiri Benc
- Viktor Malik
