## Commands Glossary 

<!-------------Template-------------->
```bash
<command>
```
**Purpose:**  **Why use it:**  
<!-------------Template-------------->


# 📂 Basic Navigation

```bash
pwd
```
**Purpose:** Shows the current working directory. **Why use it:** To confirm where you are in the file system.

```bash
ls
```
**Purpose:** Lists files and directories in the current location. **Why use it:** To see what exists inside a directory.

```bash
cd
```
**Purpose:** Changes the current directory. **Why use it:** To navigate through folders.

```bash
mkdir
```
**Purpose:** Creates a new directory. **Why use it:** To organize files or prepare workspace folders.

```bash
rm
```
**Purpose:** Removes files or directories. **Why use it:** To delete unneeded files.


# 📂 File Operations

```bash
cp
```
**Purpose:** Copies files or directories. **Why use it:** To duplicate files safely before editing or moving them.

```bash
mv
```
**Purpose:** Moves or renames files. **Why use it:** To organize files or rename them.

```bash
cat
```
**Purpose:** Prints file contents to the terminal. **Why use it:** To quickly view text files.


# 📂 System Management

```bash
sudo
```
**Purpose:** Runs a command with administrator privileges. **Why use it:** Needed for system-level changes.

```bash
apt update
```
**Purpose:** Updates the package index on Ubuntu/Debian systems. **Why use it:** Needed before installing or upgrading packages.

```bash
apt upgrade
```
**Purpose:** Installs the latest versions of all available packages. **Why use it:** To keep your system up to date.


# 📂 Virtualization (KVM)

```bash
lsmod | grep kvm
```
**Purpose:** Shows loaded kernel modules and filters for KVM. **Why use it:** To verify if KVM virtualization modules are active.

```bash
sudo modprobe -r kvm_intel
```
**Purpose:** Removes the kvm_intel module from the kernel. **Why use it:** Temporarily disables KVM to troubleshoot VM issues or allow other hypervisors access.
