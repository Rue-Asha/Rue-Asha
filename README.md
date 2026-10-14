<!--
  Repo name must be exactly the GitHub username.
  Maintenance:
  - "Focus": 2 lines, touch roughly monthly. Deliberately WITHOUT a date —
    a visibly stale month costs more than the reminder is worth.
  - Site table: rows mirror the sections of Rue-Asha.github.io
    (content/projects -> /projects/, content/posts -> /writing/), in order
    of what should be read first. If a section is added or renamed there,
    change it here too.
  - Repo table: a row only once a repo is public and has real content — the
    site is not a row in it, it has its own section. Keep the pinned repos
    in the same order as the table.
-->
# Rue Asha

Computer Science student and systems administrator, working my way from operations into cloud security engineering. I keep on-prem systems running and hardened by day, and I'm learning to express the same controls as code.

Identity, segmentation and patch discipline are the same problems in cloud, with different APIs.

## Focus
<!-- Write what is true NOW. Small and real beats big and borrowed. -->
- **Infrastructure as code** — moving a hand-built homelab to declarative, with policy checks that run before apply
- **Hardening with evidence** — CIS baselines as Ansible roles, and the scan that proves they held

## Background
- **B.Sc. Computer Science** — TU Darmstadt
- **Working student, systems administration** — on-prem infrastructure, configuration management, system hardening
  <!-- TODO: name one concrete, non-sensitive practice once it can be named —
       CIS baselines? SSH/PAM hardening? Patch pipeline? Backup restore tests? -->

## [rue-asha.github.io](https://rue-asha.github.io/)

| Section | What's in it |
|---|---|
| **[Projects](https://rue-asha.github.io/projects/)** | Why the things I build are built that way — decisions and trade-offs, not install steps. Start with the [Homelab](https://rue-asha.github.io/projects/homelab/) |
| **[Writing](https://rue-asha.github.io/writing/)** | Short notes on what I learned, and what still doesn't click — [RSS](https://rue-asha.github.io/feed.xml) |

## Repositories

| Repository | What's in it |
|---|---|
| **[Homelab-Managment](https://github.com/Rue-Asha/Homelab-Managment)** | Proxmox guests provisioned with Terraform, configured with Ansible, and gated by CI |
| **[Life-Manager](https://github.com/Rue-Asha/Life-Manager)** | A self-hosted weekly-sprint todo app — one backlog, one Monday–Sunday sprint, one Today view |
| **[Rues-Arcade](https://github.com/Rue-Asha/Rues-Arcade)** | Party games for one shared device, passed around the table |
<!-- Not public yet:
| **[Hardening-as-Code](https://github.com/Rue-Asha/Hardening-as-Code)** | CIS baselines as Ansible roles, with a compliance scan that reports drift |
-->

---
<sub>[rue.asha@proton.me](mailto:rue.asha@proton.me)</sub>
