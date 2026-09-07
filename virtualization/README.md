# Virtualization — TryHackMe (Pre Security)

## Overview

This lab introduced virtualization and virtual machines. I learned how multiple operating systems can run on one physical computer and why virtualization is widely used in cybersecurity.

**Platform:** TryHackMe — Pre Security

**Status:** Completed ✅

---

## Objective

Understand how virtualization works, identify the difference between a host and a guest operating system, and explain why virtual machines are useful in cybersecurity.

---

## Environment

* Host Operating System: Windows
* Virtualization Software: VMware
* Guest Operating System: Ubuntu Linux

---

## What I Learned

### Virtualization

Virtualization is the technology that allows one physical computer to create and run multiple isolated virtual machines.

### Virtual Machine (VM)

A virtual machine is a software-based computer that behaves like a physical computer. It has its own operating system, storage, memory, and networking.

### Host

The host is the physical computer that provides hardware resources to virtual machines.

### Guest

The guest is the operating system running inside the virtual machine.

---

## Why Virtualization Matters in Cybersecurity

* Safe environment for testing malware and security tools.
* Reduces hardware costs.
* Allows multiple operating systems to run simultaneously.
* Makes creating and resetting lab environments much faster.
* Supports portability and scalability for cybersecurity labs.

---

## Security Perspective

Virtualization provides isolation between the host and guest operating systems. If a guest machine becomes infected with malware, the host is usually protected because the VM is isolated.

However, virtualization software can occasionally contain vulnerabilities that allow a VM escape attack, so isolation is strong but not absolute.

---

## Evidence

### Ubuntu Virtual Machine

Screenshot showing Ubuntu running as a guest operating system inside VMware.

---

## Reflection

### What clicked for me

I now understand the difference between a physical computer (host) and a virtual machine (guest).

### What confused me

I originally assumed the host would always be safe if the guest was compromised. I learned that virtualization provides isolation, but vulnerabilities can still exist.

### Next Step

Learn networking inside virtual machines and understand how virtual machines communicate with each other.

