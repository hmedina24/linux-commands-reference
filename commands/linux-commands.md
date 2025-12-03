## Commands Glossary

```bash
lsmod \| grep kvm
```
**Purpose:** Shows loaded kernel modules and filters for KVM.  
**Why use it:** To verify if KVM virtualization modules are active.  

```bash
sudo modprobe -r kvm_intel
```
**Purpose:** Removes the kvm_intel module from the kernel.
**Why use it:**Temporarily disables KVM to troubleshoot VM issues or allow other hypervisors access.
  