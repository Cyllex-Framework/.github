<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Cyllex-Framework/.github/main/profile/cyllex-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Cyllex-Framework/.github/main/profile/cyllex-light.png">
  <img src="https://raw.githubusercontent.com/Cyllex-Framework/.github/main/profile/cyllex-dark.png" alt="Cyllex" width="340">
</picture>

AI-driven threat intelligence and adversary emulation.

<a href="https://cyllex.io">cyllex.io</a> ·
<a href="https://x.com/CyllexFramework">X</a> ·
<a href="mailto:contact@cyllex.io">contact@cyllex.io</a>

</div>

---

Cyllex is a project that applies AI to real cybersecurity work: threat intelligence,
adversary emulation, detection, and sharing what we learn along the way. The point is to
let AI handle the heavy lifting of research, reading piles of reports and tracking what an
adversary actually does, so the analyst can focus on the judgement. It's built by people
who care about this and want to do it well.

## What we work on

- Threat intelligence: collecting sources, reading them, and building a clear, sourced
  picture of a threat.
- Adversary emulation: running real techniques against a target.
- Detection: proving whether your SIEM/EDR actually caught them.
- Knowledge: writing it down and sharing it openly.

## Projects

**Argus** is a local-first, AI-powered threat intelligence tool. Given a threat, an actor,
a campaign, a piece of malware or a tool, it searches for sources, reads the reports, and
extracts what each one claims, with a verbatim quote behind every claim. It then
consolidates those claims into a confidence-scored view mapped to MITRE ATT&CK, separating
what several sources corroborate from what rests on a single source or is contested. From
there it can generate framework-ready TTPs and Sigma rules, export STIX, and serve it all
over TAXII.

**Proteus** is a self-contained purple-team framework for adversary emulation and
detection validation. It runs real MITRE ATT&CK techniques across agent, agentless
(WinRM/SSH), cloud and container targets, then correlates each one against your SIEM/EDR
to answer whether detection actually fired. It ships with its own library of techniques
and runs on its own. It can also load TTP packs from other sources when you want it to.

Both repositories are private for now.

## Author

Cyllex is built by Raúl Redondo.
[X](https://x.com/_RayRT) · [Web](https://rayrt.gitlab.io/) · [LinkedIn](https://www.linkedin.com/in/ra%C3%BAlredondo/)
