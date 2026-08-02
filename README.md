<!--
  Repo name must be exactly the GitHub username.

  Maintenance:
  - "Focus": 2 lines, touch roughly monthly. Deliberately WITHOUT a date —
    a visibly stale month costs more than the reminder is worth.
    Add a date only once the monthly routine actually holds.
  - Site section: the three rows mirror content/ in Rue-Asha.github.io.
    If a section is added or renamed there, change it here too.
  - Repo table: kept commented out below. Uncomment it only once a repo is
    public and has real content — the site is not a row in it, it has its
    own section.
-->

# Rue Asha

Computer Science student and systems administrator, working my way from operations into security engineering.

I spend my days keeping on-prem systems running and hardened, and my evenings learning how they break. This profile is where I document both.

---

### Focus

<!-- Write what is true NOW. Small and real beats big and borrowed.
     The more specific version comes in four months, when it holds. -->

- **Security foundations** — currently the defensive modules: logging, monitoring, and the tooling side of detection
- **Homelab** — building an environment to test hardening against my own attacks, and to see what the logs actually show while it happens

### Background

- **B.Sc. Computer Science** — TU Darmstadt
- **Working student, systems administration** — on-prem infrastructure, system hardening
  <!-- TODO: add one concrete, non-sensitive detail once it can be named —
       CIS baselines? SSH/PAM hardening? Patch pipeline? Backup restore tests? -->

### How I write things up

I write these for future-me first, which means the reasoning stays in — including the dead ends, because that is usually where the actual learning was.

What I keep coming back to comes from the operations side of my day job: plenty of people can walk a box, far fewer can say what the defender should have seen in the logs while it happened.

### On-prem, and where it goes next

Cloud is where the industry is heading and I'm building the fundamentals for it. On-prem is where I'm learning them from: identity, network segmentation and patch discipline are the same problems with different APIs, and working at the config level means seeing the mechanics rather than the abstraction.

---

## [rue-asha.github.io](https://rue-asha.github.io/)

Everything I write lands in one place — a Hugo site, source in [`Rue-Asha.github.io`](https://github.com/Rue-Asha/Rue-Asha.github.io), rebuilt on every push to `main`. Three sections:

| Section | What's in it |
|---|---|
| **[Writeups](https://rue-asha.github.io/writeups/)** | Boxes, labs and CTF challenges — recon through root, reasoning left in. Grouped by platform: [HackTheBox](https://rue-asha.github.io/writeups/hackthebox/), [TryHackMe](https://rue-asha.github.io/writeups/tryhackme/), [CTF](https://rue-asha.github.io/writeups/ctf/) |
| **[Projects](https://rue-asha.github.io/projects/)** | Living documentation for what I build — homelab, life dashboard, party games. One folder per project, so a page can grow into a handbook |
| **[Journal](https://rue-asha.github.io/blog/)** | Short essays: what I learned this week, and what still doesn't click |

Two rules keep it from rotting. Setup steps, commands and deploy instructions stay in each repo's README, next to the code that keeps them honest — the project pages carry the reasoning instead: why SQLite and not Postgres, what the trade-off costs, when it would stop being the right call. And there are no tags or categories: the section says what kind of page it is, the folder says which platform, and full-text search covers everything else without a vocabulary I'd have to hand-maintain.

Scope, for the avoidance of doubt: every technique documented there was applied to systems I own or was explicitly authorised to test — retired HackTheBox machines, TryHackMe rooms, CTF infrastructure, and my own homelab.

<!-- Repositories — uncomment the heading, the table header and a row once that
     repo is public and has real content. Keep the pinned repos in the same
     order as the table. The site itself is deliberately NOT a row here; it has
     its own section above.

### Repositories

| Repository | What's in it |
|---|---|
| **[Homelab-Managment](https://github.com/Rue-Asha/Homelab-Managment)** | Ansible-managed Proxmox host: what runs where, and why |
| **[Life-Managment-Dashboard](https://github.com/Rue-Asha/Life-Managment-Dashboard)** | One self-hosted app for tasks, uni, notes and finances |
| **[Party-Game-Web-App](https://github.com/Rue-Asha/Party-Game-Web-App)** | Party games for a single screen — a study in deleting architecture |
-->

---

<sub>Reach me via rue.asha@proton.me</sub>
