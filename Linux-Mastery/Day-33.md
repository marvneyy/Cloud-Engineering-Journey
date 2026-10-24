# 📅Day 33 — Linux File Permissions and Ownership

## 🎯 Goal
Understand Linux file permissions and ownership by creating and running a simple shell script.

### 1. What Is a Script?

A **script** is a file containing commands that the computer can execute.

Example:

```bash
echo "Hello, Marvan!"
```

When the script runs, it prints:

```text
Hello, Marvan!
```

### 2. Create a Script File

```bash
touch script.sh
```

**Purpose:** Creates an empty file named `script.sh`.

Write a command into the file:

```bash
echo 'echo "Hello, Marvan!"' > script.sh
```

**Purpose:** Saves the `echo "Hello, Marvan!"` command inside `script.sh`.

### 3. Check File Permissions

```bash
ls -l script.sh
```

Example output before adding execute permission:

```text
-rw-rw-r-- 1 user user ... script.sh
```

#### Understanding `rwx`

- `r` = Read — permission to read the file.
- `w` = Write — permission to modify the file.
- `x` = Execute — permission to run the file.

The first three permission characters apply to the owner, the next three to the group, and the last three to others.

### 4. Add Execute Permission

Try running the script:

```bash
./script.sh
```

Initially, the terminal returned:

```text
Permission denied
```

The file did not have execute permission.

Add execute permission:

```bash
chmod +x script.sh
```

**Purpose:** Adds execute permission to the file.

Run the script again:

```bash
./script.sh
```

Expected output:

```text
Hello, Marvan!
```

### 5. Change File Ownership

Change the file owner to `deployer`:

```bash
sudo chown deployer script.sh
```

**Purpose:** Changes the file owner to the Linux user `deployer`.

Check the ownership:

```bash
ls -l script.sh
```

My verified output showed:

```text
-rwxrwxr-x 1 deployer user ... script.sh
```

This confirms:
- Owner: `deployer`
- Group: `user`
- Execute permission: present

### 6. Important Commands

| Command | Purpose |
|---|---|
| `touch script.sh` | Create a file |
| `echo 'echo "Hello, Marvan!"' > script.sh` | Write a command into the file |
| `ls -l script.sh` | Check permissions and ownership |
| `chmod +x script.sh` | Add execute permission |
| `sudo chown deployer script.sh` | Change the file owner |
| `./script.sh` | Run the script |

### 7. Key Takeaways

- A script is a file containing commands.
- `r`, `w`, and `x` represent read, write, and execute permissions.
- `chmod` changes file permissions.
- `chown` changes file ownership.
- `ls -l` displays file permissions, owner, and group.
- Linux permissions help control access to files on servers.

## ✅ Day 33 Practical Checklist

- [x] Created `script.sh`
- [x] Wrote a command into the script
- [x] Observed the `Permission denied` error
- [x] Added execute permission
- [x] Successfully ran the script
- [x] Changed the owner to `deployer`
- [x] Verified the owner and permissions

**Status:** Practical completed and verified.
Day 33 — Linux File Permissions and Ownership

## 🎯 Goal
Understand Linux file permissions and ownership by creating and running a simple shell script.

## 1. What Is a Script?

A **script** is a file containing commands that the computer can execute.

Example:

```bash
echo "Hello, Marvan!"
```

When the script runs, it prints:

```text
Hello, Marvan!
```

## 2. Create a Script File

```bash
touch script.sh
```

**Purpose:** Creates an empty file named `script.sh`.

Write a command into the file:

```bash
echo 'echo "Hello, Marvan!"' > script.sh
```

**Purpose:** Saves the `echo "Hello, Marvan!"` command inside `script.sh`.

## 3. Check File Permissions

```bash
ls -l script.sh
```

Example output before adding execute permission:

```text
-rw-rw-r-- 1 user user ... script.sh
```

### Understanding `rwx`

- `r` = Read — permission to read the file.
- `w` = Write — permission to modify the file.
- `x` = Execute — permission to run the file.

The first three permission characters apply to the owner, the next three to the group, and the last three to others.

## 4. Add Execute Permission

Try running the script:

```bash
./script.sh
```

Initially, the terminal returned:

```text
Permission denied
```

The file did not have execute permission.

Add execute permission:

```bash
chmod +x script.sh
```

**Purpose:** Adds execute permission to the file.

Run the script again:

```bash
./script.sh
```

Expected output:

```text
Hello, Marvan!
```

## 5. Change File Ownership

Change the file owner to `deployer`:

```bash
sudo chown deployer script.sh
```

**Purpose:** Changes the file owner to the Linux user `deployer`.

Check the ownership:

```bash
ls -l script.sh
```

My verified output showed:

```text
-rwxrwxr-x 1 deployer user ... script.sh
```

This confirms:
- Owner: `deployer`
- Group: `user`
- Execute permission: present

## 6. Important Commands

| Command | Purpose |
|---|---|
| `touch script.sh` | Create a file |
| `echo 'echo "Hello, Marvan!"' > script.sh` | Write a command into the file |
| `ls -l script.sh` | Check permissions and ownership |
| `chmod +x script.sh` | Add execute permission |
| `sudo chown deployer script.sh` | Change the file owner |
| `./script.sh` | Run the script |

## 7. Key Takeaways

- A script is a file containing commands.
- `r`, `w`, and `x` represent read, write, and execute permissions.
- `chmod` changes file permissions.
- `chown` changes file ownership.
- `ls -l` displays file permissions, owner, and group.
- Linux permissions help control access to files on servers.

## ✅ Day 33 Practical Checklist

- [x] Created `script.sh`
- [x] Wrote a command into the script
- [x] Observed the `Permission denied` error
- [x] Added execute permission
- [x] Successfully ran the script
- [x] Changed the owner to `deployer`
- [x] Verified the owner and permissions

**Status:** Practical completed and verified.
