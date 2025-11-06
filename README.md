# -Linux-IAM-Hardening

# Minor Project 1 – Linux IAM & Hardening

### Users, Groups, and Permissions

---

## Objective

Design and implement a secure user, group, and permission model on an Ubuntu server.
Identify three security misconfigurations in a vulnerable lab environment, fix them, and document the remediation process.

---

## Tools and Environment

* Ubuntu Virtual Machine (VM)
* Kali Linux or any attacker VM (for testing)
* Sudo access to lab VM

---

## Tasks

### Task 1: User, Group, and Permission Setup

1. Create a baseline access control policy for roles such as admin, dev, and auditor.
2. Create groups and users according to the policy using commands like groupadd and useradd.
3. Assign minimal privileges using the principle of least privilege.
4. Configure sudo rules carefully in /etc/sudoers.
5. Apply correct file permissions and ACLs on shared folders.
6. Enable and configure auditd to log changes to /etc/sudoers and /etc/passwd.

### Task 2: Vulnerability Analysis and Fix

1. Identify at least three security misconfigurations in a vulnerable system snapshot.
   Examples:

   * World-writable /etc/cron.d
   * Unrestricted NOPASSWD sudo rule
   * Weak permissions on system files
2. Fix these issues and record before/after proof using commands like ls -l and getfacl.
3. Prepare a remediation checklist and a short user management policy document.

---

## Deliverables

* Policy document
* Remediation report with screenshots or logs
* Checklist of fixes
* Evidence of secure configuration

---

## Skills and Learning Outcomes

* Linux user and group management
* Principle of least privilege
* Secure sudo configuration
* File permission and ACL control
* Auditing with auditd
* Vulnerability detection and remediation

---

## Summary

This project demonstrates how to design and maintain a secure Linux environment through proper IAM configuration, least privilege principles, and basic system hardening practices.

