# AOSV

#### :warning: This repository is (sadly) not active anymore.

Feel free to fork and extend it.

A useful resource (a bit updated) over concepts in the linux kernel can be
found in
[A Heavily-Commented Linux Kernel Source Code](http://www.oldlinux.org/download/ECLK-5.0-WithCover.pdf)


### :boom: [Related Project](https://github.com/beabevi/LKM-Fibers)

The **project** developed for the course can be found [here](https://github.com/beabevi/LKM-Fibers).
It covers some nice topics about kernel programming and it is relatively succint
in its implementation.

------------

The repository holds the lecture notes of Spring 2018 of the Advanced Operating
Systems and Virtualization course held by Alessandro Pellegrini. There are two
branches, namely `online` and `master`. In the former there are the notes as
taken in class while the latter are the notes rewritten with the support of
integrating material, classmates and professor.

The repo is a bit dirty in its current state and the `online` version of
lectures <= 5 does not really exist.

Some lectures have in the reference part stuff that is unrelated to the
lecture just because new folders are created by copying and pasting older ones.


## Browsing the Linux Kernel

* [Linux Cross Reference (LXR)](https://elixir.bootlin.com/)
* [livegrep](https://livegrep.com/search/linux)
* [ag - the_silver_searcher](https://github.com/ggreer/the_silver_searcher)

## Tagged Content


* **Lec1**: course information, boot sequence introduction, master boot record
            BIOS
* **Lec2**: A20 line, protected mode, LDT, GDT, protection, IDT, privilege
            level switch, Task State Segment (TSS)
* **Lec3**: protected mode paging, i386 paging, PDE/PTE fields, PAE, addressing
            in long mode, Translation Lookaside Buffer (TLB), longmode enable,
            Linux Boot i386 (< v.2.6), UEFI, GUID Partitioning Scheme, Secure
            Boot, Bootkits, Platform Key (PK), Key Exchange Key (KEK), Signature
            Database, Multicore Booting (SMP), APIC, INIT-SIPI
* **Lec4**: Linux Boot Protocol, Kernel Initialization, `header.S`, `main`,
            `go_to_protected_mode`, GDT/IDT dummy setup, `protected_mode_jump`,
            `head_{32,64}.S`, `startup_{32,64}`, `start_kernel`, Inline Assembly,
            `volatile`, `asmlinkage`, regparm, `__visible`, `__init`
* **Lec5**: Early paging setup 32bit, bootmem allocator, paging in linux, kernel
            page table initialization, TLB APIs, NUMA
* **Lec6**: Memory Management, Zones, `mem_map`, Buddy System, Buddy
            Allocation/Deallocation APIs, High Memory (`HIGHMEM`), `vmap`, `kmap`,
            `kmap_atomic`, NUMA Allocation Policies
