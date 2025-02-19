# Exercise 4-0: Red Hat Ansible Tower Setup

## Table of Contents

- [Objective](#Objective)
- [Guide](#Guide)

# Objective

Demonstrate setup for Red Hat Ansible Tower.  To run an Ansible Playbook in Tower we need to create a **Job Template**.  A **Job Template** requires:
 - An **Inventory** to run the job against
 - A **Credential** is used to login to devices.
 - A **Project** which contains Playbooks

# Guide

Before beginning your Ansible Tower labs please upgrade your Red Hat Ansible Tower control node to the latest version of Ansible.  We will be using a newer feature only available on Ansible 2.8 which is not installed by default in this lab yet:

```
sudo yum update ansible -y
```

There are multiple ways we can quickly setup Red Hat Ansible Tower.  For this workshop we are giving you two options.  You can use Ansible Playbooks to help automate the setup, or you can manually use the web user interface (UI) to help better understand the Tower concepts.  Feel free to user either method.

 - [Manual Approach](README-manual.md)

---
[Click Here to return to the Ansible - Network Automation Workshop](../../README.md)
