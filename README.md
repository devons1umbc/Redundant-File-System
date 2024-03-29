# Redundant File System (CMSC621)

To set up a storage node VM, you need to place `storage_node.py` in the `Desktop` of the system. Your user needs to be called `cmsc621` and the password needs to be `12345`. On the desktop, you also need directories `files`, `deleted`, `quarantine`, and `templates` (this on is for the web pages for nodes). You also need to go into /etc/ssh/ssh_config and uncomment `StrictHostKeyChecking` and set its value to `no`.

To set up a master VM, place `main.py` in the `Desktop` of the system. The Master needs to have the same username and password as the storage nodes. On the desktop, you need `nodes`, `users`, `masters` (fill this directory manually with files of all existing masters' ips, both primary and shadow masters), and `templates`. Make the same ssh changes as above.

An IEEE-style paper explaining Redundant File System in depth: [The Redundant File System Designing a Resilient and Scalable File System.pdf](https://github.com/devons1umbc/Redundant-File-System/files/14320516/The.Redundant.File.System.Designing.a.Resilient.and.Scalable.File.System.pdf)
