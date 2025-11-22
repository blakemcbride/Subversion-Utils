# Subversion Utility Scripts

This repository contains a collection of Bash utilities designed to simplify and streamline common **Subversion (SVN)** operations. These scripts make it easier to create branches and tags, list repository structures, examine logs, sync working copies, and more — all from the command line.

These utilities were designed to be used with bash under Linux.  They may work elsewhere.

---

## Included Commands

### `svn-branch`
Utility for creating and managing branches.  
Supports displaying existing branches and identifying the current branch.

### `svn-diff`
Simplifies viewing diffs between working copy changes or repository paths.

### `svn-list`
Displays repository layout such as `/trunk`, `/branches`, and `/tags`.

### `svn-log`
Provides formatted log output with optional filtering.

### `svn-new`
Helps create a fresh working copy from trunk or a branch.

### `svn-sync`
Synchronizes a working copy with its corresponding repository source.

### `svn-tag`
Creates tags without requiring extra metadata parameters.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/<your-repo>.git
```

Place the scripts somewhere in your PATH:

```bash
sudo cp svn-* /usr/local/bin/
sudo chmod +x /usr/local/bin/svn-*
```

Verify installation:

```bash
svn-list
```

---

## Requirements

- Bash
- Subversion client (`svn`)
- Standard repository layout (`trunk/`, `branches/`, `tags/`)

---

## Acknowledgment

These utilities were created and enhanced by Blake McBride with the assistance of **ChatGPT**.
