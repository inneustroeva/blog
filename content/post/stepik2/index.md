---
# Documentation: https://docs.hugoblox.com/managing-content/

title: "Stepik2"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2025-05-04T21:08:42+03:00
lastmod: 2025-05-04T21:08:42+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Hello friends, today I continue to write a post about my Stepika course and today the topic of my post is: PC/Phone protection

# How and why to encrypt a hard drive?e?

Disk encryption protects data in case of loss or theft of the device. Without the key, the attacker will not gain access to the files.

### How it works:

Encryption key generation (usually AES-256)

Data encryption (of the entire disk or individual partitions)

Access only after entering the password

### Popular tools:

Windows: BitLocker

mac OS: FileVault

Linux: LUKS

Free: VeraCrypt

Important: the key must be stored separately from the encrypted disk (on a USB flash drive, in the TPM module, or with the administrator).

# How do I create and store strong passwords?

A password is the main way to protect your data. A good password:

Long (12+ characters)

Contains letters (upper/lower case), numbers, and special characters

Unique for each service

### Popular errors:

Simple combinations (12345, qwerty)

Repeating passwords on different websites

How are passwords stored on servers?

Hash functions (SHA-2, SHA-3, GOST) are used

A "salt" (random data) is added to protect weak passwords.

### Safety Tips:

Use a password manager (Keepassx, Keychain)

Enable two-factor authentication

Change passwords regularly

Check for leaks on haveibeenpwned.com

### Conclusion: A long, complex and unique password + manager = reliable protection.
