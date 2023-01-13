
# Content <!-- omit in toc -->

- [Title]()
  - [SubTitle]()



- [Basics](#basics)
  - [File Hierarchy Standard (FHS)](#file-hierarchy-standard-fhs)
  - [Commands](#commands)
- [Disk and File System Management](#disk-and-file-system-management)
  - [General Disk Manipulation (non-LVM)](#general-disk-manipulation-non-lvm)
  - [Globs (Wildcards)](#globs-wildcards)
  - [Regex](#regex)
  - [Stream redirection](#stream-redirection)
- [Text Readers & Editors](#text-readers--editors)
  - [Less](#less)
  - [VI](#vi)
- [User and Group Management](#user-and-group-management)
- [File System Permissions](#file-system-permissions)
- [SSH](#ssh)
- [Cronjobs](#cronjobs)
- [Package Management](#package-management)
  - [RPM](#rpm)
  - [YUM](#yum)
- [📃 List of commands by category:](#-list-of-commands-by-category)
  - [Directory Navigation](#directory-navigation)
  - [File Commands](#file-commands)
  - [File and Directory Manipulation](#file-and-directory-manipulation)
  - [Package archive and compression tools](#package-archive-and-compression-tools)
  - [System commands](#system-commands)
  - [Networking Commands](#networking-commands)
  - [Package Management](#package-management-1)
  - [User Information commands](#user-information-commands)
  - [Session commands](#session-commands)
  - [Getting Help](#getting-help)
  - [Applications](#applications)
- [📃 List of commands by chapter:](#-list-of-commands-by-chapter)
- [🔗Links](#links)
- [📖Other eBooks](#other-ebooks)
- [🤲Contributing](#contributing)

---

# Basics

## File Hierarchy Standard (FHS)

| Path     | Content                             |
| -------- | ----------------------------------- |
| `/bin`   | Binaries (User)                     |
| `/boot`  | Static boot loader files            |
| `/etc`   | Host specific configs               |
| `/lib`   | Shared libraries and kernel modules |
| `/sbin`  | Binaries (System/root)              |
| `/var`   | Varying files (e.g. Logs)           |
| `/usr`   | 3rd party software                  |
| `/proc`  | Pseudo file system                  |
| `/sys`   | Pseudo file system                  |
| `/mnt`   | Mountpoint for internal drives      |
| `/media` | Mountpoint for external drives      |
| `/home`  | User homes                          |
| `/run`   | PID files of running processes      |

---

## Commands

**File System Commands**

| Command | Options            | Description                                       |
| ------- | ---------------- | ------------------------------------------------- |
| [`cd`](https://github.com/bobbyiliev/101-linux-commands-ebook/blob/main/ebook/en/content/002-the-cd-command.md)    | `-`              | Navigate to last dir                              |
|         | `~`              | Navigate to home                                  |
|         | `~username`      | Navigate to home of specified user                |
| [`pwd`](https://github.com/bobbyiliev/101-linux-commands-ebook/blob/main/ebook/en/content/006-the-pwd-command.md)   |                  | Print working dir                                 |
| [`ls`](https://github.com/bobbyiliev/101-linux-commands-ebook/blob/main/ebook/en/content/001-the-ls-command.md)    |                  | Print dir content                                 |
|         | `-l`             | Format as list                                    |
|         | `-a`             | Show hidden items (`-A` without `.` and `..`)     |
|         | `-r`             | Invert order                                      |
|         | `-R`             | Recurse                                           |
|         | `-S`             | Sort by size                                      |
|         | `-t`             | Sort by date modified                             |
| [`mkdir`](https://github.com/bobbyiliev/101-linux-commands-ebook/blob/main/ebook/en/content/014-the-mkdir-command.md) | `-p`             | Create dir with parents                           |
| [`cp`](https://github.com/bobbyiliev/101-linux-commands-ebook/blob/main/ebook/en/content/031-the-cp-command.md)    | `-r`             | Copy dir                                          |
| [`rmdir`](https://github.com/bobbyiliev/101-linux-commands-ebook/blob/main/ebook/en/content/103-the-rmdir-command.md) | `-p`             | Remove dir and empty parents                      |
| [`rm`](https://github.com/bobbyiliev/101-linux-commands-ebook/blob/main/ebook/en/content/040-the-rm-command.md)    | `-rf`            | Remove dir recursively, `-f` without confirmation |
| [`mv`](https://github.com/bobbyiliev/101-linux-commands-ebook/blob/main/ebook/en/content/032-the-mv-command.md)    |                  | Move recursively                                  |
| [`find`](https://github.com/bobbyiliev/101-linux-commands-ebook/blob/main/ebook/en/content/102-the-find-command.md)  | `-iname pattern` | Search dir/file case-insensitive                  |
|         | `-mmin n`        | Last modified n minutes ago                       |
|         | `-mtime n`       | Last modified n days ago                          |
|         | `-regex pattern` | Path matches pattern                              |
|         | `-size n[kMG]`   | By file size (`-n` less than; `+n` greater than)  |
|         | `! searchparams` | Invert search                                     |

---
