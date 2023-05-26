# FOS-Operating-System-Project

# Introduction:
The Faculty of Computer and Information Science OS (FOS) project was undertaken with the
objective of gaining practical experience and deepening our understanding of operating
systems. This report documents the progress and outcomes of the project, which involved the
implementation of specific functions within the FOS educational operating system.
The project was divided into two milestones, each focusing on distinct objectives. In the first
milestone, our primary goal was to implement essential functionality related to memory
management. This involved the development of functions such as “kmalloc”, “kfree”,
“kheap_physical_address”, and “kheap_virtual_address”. These functions enabled the kernel
to dynamically allocate and free memory space at runtime, thereby enhancing the efficiency
and flexibility of the operating system.
Building upon the achievements of the first milestone, the second milestone aimed to handle
page faults during execution and introduce user-level memory management capabilities.
Functions implemented during this phase included “page_fault_handler_with_buffering”,
“malloc”, “allocate_mem”, “free”, and “free_mem_with_buffering”. By applying the
MODIFIED CLOCK replacement algorithm, the operating system effectively handled page faults,
while user programs were empowered to dynamically allocate and free memory space at
runtime.
The implementation of these functions within the FOS operating system provided us with
practical insights into operating system concepts and allowed us to apply our theoretical
knowledge in a real-world context. Additionally, it contributed to the usability and versatility of
the FOS OS, enhancing its educational value for future learners.
In the following sections, we will provide a comprehensive overview of the milestones, detailing
the specific functions implemented, the methodologies employed, and the progress achieved in
each milestone. By documenting our experiences and accomplishments, this report aims to
contribute to the knowledge base in operating system development and serve as a valuable
resource for future projects and learning endeavors.

# Overview:
### Milestone 1: 
Kernel Heap
In the first milestone, our focus was on implementing fundamental memory management
functionality within the FOS operating system. The following functions were developed:
1. Kmalloc: This function allowed the kernel to dynamically allocate memory space at
runtime, providing flexibility for efficient memory management.
2. Kfree: With this function, the kernel could release previously allocated memory, freeing up
resources and improving memory utilization.
3. kheap_physical_address: This function provided the physical address of a given virtual
address within the kernel heap, enabling precise memory mapping.
4. kheap_virtual_address: By returning the virtual address corresponding to a given physical
address within the kernel heap, this function facilitated seamless memory access and
manipulation.
The successful implementation of these functions in Milestone 1 established the foundation for
advanced memory management capabilities within the FOS operating system.

### Milestone 2: 
User Heap and Page Fault Handling
In the second milestone, we expanded the functionality of the FOS OS by introducing user-level
memory management and robust page fault handling. The following functions were
implemented:
1. page_fault_handler_with_buffering: This function handled page faults during program
execution, utilizing the MODIFIED CLOCK replacement algorithm to efficiently manage
memory pages.
2. Malloc: Enabling dynamic memory allocation within user programs, this function allowed
users to request memory space as needed.
3. allocate_mem: With this function, users could allocate memory of a specific size within
their programs, promoting flexibility and efficient resource utilization.
4. Free: This function provided users with the ability to release allocated memory, freeing up
resources and preventing memory leaks.
5. free_mem_with_buffering: By incorporating a buffering mechanism, this function
enhanced the efficiency of memory de-allocation, improving overall performance.
The successful implementation of these functions in Milestone 2 extended the capabilities of
the FOS operating system, enabling user-level memory management and robust handling of
page 

### FOS [Link](https://drive.google.com/drive/folders/1I0kHn7cTYAH6mSirov5nnft-0bNpzva2?usp=share_link)

**Directed By:**

* [Eslam Shouman](https://www.linkedin.com/in/eslam-shouman-0958091b4/)

* [Rawan ibrahim](https://www.linkedin.com/in/rawan-ibrahim-a01778268) 

* [Mohamed Mahmoud](https://www.linkedin.com/in/mohamed-mahmoud07) 
