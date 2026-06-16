BoSOS-Run

The BoS OS helps you understand and manage your company operating system.

Most companies add AI tools on top of an operating system nobody has written down. Strategy lives in the founder's head. Roles blur. Decisions don't stick. AI amplifies whatever's already there. Clarity becomes velocity; muddle becomes noise.

The Run skill is where the OS stops being a document and starts doing work.

## What this skill does

**Run** operates the OS day to day — shaping missions, staffing them with agents, and driving delivery against your North Star metric.

Run contains three agents that work in sequence:

- **Mission Shaper** takes a rough idea or a problem and coaches it into a Mission Brief. It doesn't tell you what to do — it asks the questions that surface what the mission actually is, what success looks like, and what would block it.
- **Agent Planner** reads the Mission Brief and staffs the mission. It identifies which agents should run it, what their decision boundaries are, and what the escalation path looks like.
- **Delivery Manager** runs the day-to-day backlog. It tracks what's in progress, what's blocked, and what's done — and keeps the mission moving without needing to be asked.

> **Bootstrap → Workshop → Run:** Bootstrap creates your OS from public information. Workshop refines it with your insider knowledge. Run operates it. Do them in order.

---

## How it works

Every company already has an operating system. Most just don't know what's in it.

[![Every Company OS Ever](https://raw.githubusercontent.com/BoSMark/BoS_OS_Start/main/images/Every_Company_OS.png)](https://raw.githubusercontent.com/BoSMark/BoS_OS_Start/main/images/Every_Company_OS.png)

The BoS OS maps that structure, then gives AI a governed place inside it.

[![The same structure with AI inside](https://raw.githubusercontent.com/BoSMark/BoS_OS_Start/main/images/Company_OS_With_AI.png)](https://raw.githubusercontent.com/BoSMark/BoS_OS_Start/main/images/Company_OS_With_AI.png)

Your folder structure is your system. The files are the memory.

---

## Getting started

The Run skill file is maintained in the canonical repo:

- **[BoS-OS-Start](https://github.com/BoSMark/BoS_OS_Start)**

**Note:** Run includes the **Agent Spec Builder** sub-skill (`/skills/agent-spec-builder/SKILL.md`), used by Agent Planner to spec individual agents with decision boundaries, escalation triggers, and evaluation criteria.

Install from there. Full installation instructions are in that repo.

> **Important:** Run must be used inside a Cowork project with a folder selected — the same one you used for Bootstrap and Workshop. If you run it from a general Claude conversation, files won't save and you'll need to start again.

---

## What comes before Run

Run requires Bootstrap and Workshop to have completed first. If you haven't done that:

1. Install `agent-os-bootstrap.skill` from the [BoS_OS_Start release page](https://github.com/BoSMark/BoS_OS_Start/releases/latest)
2. Run Bootstrap: type **Bootstrap my company OS** in your Cowork project
3. Install `agent-os-workshop.skill` and run Workshop to harden your strategy documents and agent specs
4. Then install `agent-os-run.skill` and start with Mission Shaper

Run is designed to pick up exactly where Workshop left off. It reads your agent specs, your strategy documents, and your North Star metric — and works with them.

---

## What Run produces

Each mission produces a set of state files that persist across sessions:

- **mission-brief.md** — what the mission is, what success looks like, what would block it
- **todo.md** — the full task backlog
- **in-progress.md** — what's actively being worked
- **blocked.md** — what's stuck and why
- **done.md** — the completed record

These files are your audit trail. They also let any session pick up exactly where the last one left off.

---

## What comes next

Run is the operational layer. As your OS matures, new agent specs and mission templates are released on an ongoing basis.

- Full toolkit — [BoS-OS-Start](https://github.com/BoSMark/BoS_OS_Start)
- Bootstrap only — [BoSOS-Bootstrap](https://github.com/BoSMark/BoSOS-Bootstrap)
- Workshop only — [BoSOS-Workshop](https://github.com/BoSMark/BoSOS-Workshop)

---

## More skills, tasks, and agents

Further skills, scheduled tasks, and agent specs are released on an ongoing basis.

**Follow or watch this repo** to get notified when new ones ship.

All BoSMark repos — [github.com/BoSMark](https://github.com/BoSMark)

---

## Stay in the loop

Workshops, user groups, and community support:

**[businessofsoftware.org/updates](https://www.businessofsoftware.org/updates)**

Subscribe for workshop announcements, guided cohorts, and peer community access.

---

*Built by Tim Barker, Mark Littlewood and [Business of Software](https://businessofsoftware.org) — helping software founders build profitable, enduring companies since 2007.*
