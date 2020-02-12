---
title: Code commits
img: 1.png
---

### Action

Developers **commit code** to a version control system such as [Git].

### Threat

An attacker **inserts malicious code** into the project's version control system.

> **Examples**: [Juniper] routers, [Linux] kernel

### Partial prevention

Require developers to [sign commits]. This makes it harder for a repository compromise or developer machine compromise to make a code modification. It also provides non-repudiation if there is a hack so that in most cases it is clear which developer was compromised.  Using 2FA or hardware tokens for developer access further increases the attack difficulty.

[git]: https://git-scm.com
[juniper]: https://www.juniper.net/us/en/products-services/routing
[linux]: https://linux.org
[sign commits]: https://help.github.com/en/github/authenticating-to-github/signing-commits