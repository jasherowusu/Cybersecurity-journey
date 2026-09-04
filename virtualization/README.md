# Virtualization

## What I Learned

- 
- 
- 

## Key Concepts

### Virtualization

My understanding:

### Virtual Machine

My understanding:

### Host

My understanding:

### Guest

My understanding:

## Hands-On Practice

Commands/tools I used:

bash
whoami
hostname
uname -a
ip addr




Virtualization is the technology that allows one physical computer (the host) to create and run multiple isolated virtual computers (virtual machines), each with its own operating system and resources. 

A virtual machine (VM) is a software-based computer that behaves like a real computer. It has its own operating system, memory, storage, CPU allocation, and network connection, but it runs inside a host machine. 

host- The host is the physical computer that provides hardware resources (CPU, RAM, storage, networking) to virtual machines through a hypervisor such as VMware or VirtualBox. 
Guest- A guest is the operating system running inside a virtual machine. 



Benefit                                            Cybersecurity Example
Safe Testing                                       Run malware without infecting the host.
Cost Saving                                        No need to buy three physical computers.
Flexibility                                        Run Ubuntu, Kali, Windows simultaneously.
Portability                                        Move a VM to another computer.
Faster Deployment                                  Create or clone VMs quickly.
Scalability                                        Add more VMs as needed.
Centralized Management                             Manage multiple VMs from one host.





If the Guest Gets Compromised...
Isolation protects the host most of the time

Normally

The host is protected because the VM is isolated.

However, if there's a vulnerability in the virtualization software (VMware/VirtualBox/Hyper-V), attackers can sometimes perform a VM Escape and reach the host.

Isolation- Isolation means the guest operating system runs in its own separate environment with dedicated virtual resources. Activities inside the VM normally do not directly affect the host or other virtual machines.
