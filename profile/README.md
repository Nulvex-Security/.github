<p align="center">
  <img src="https://nulvex.com/nulvex-favicon.svg" width="96" alt="Nulvex">
</p>

<h1 align="center">Nulvex Security</h1>

<p align="center"><b>Secure by architecture.</b><br>
Nulvex is a cybersecurity company for businesses: assessment, hardening, monitoring and
incident response. Architecture first, tools second.<br>
This is where we publish our security research and detection rules.</p>

---

### What is here

| Repository | What it is |
|---|---|
| [nulvex-detections](https://github.com/Nulvex-Security/nulvex-detections) | Sigma, Suricata and Wazuh rules, each linked to the analysis behind it. Each one states its expected telemetry, its false positives, and whether it has actually been tested |

More will follow as there is real content to put in it. We would rather have one useful
repository than five empty ones.

### Research

Vulnerability analysis written for the people who have to act on it: who is really exposed,
what to do, and what we could not establish. Published at
**[nulvex.com/research](https://nulvex.com/research)**.

**[The CVE Library](https://nulvex.com/research/library/)**: 2,350 serious and actively exploited
vulnerabilities, searchable by product, with exploitation status and fixes. Updated weekly.
**[Exploited this month](https://nulvex.com/research/threat-intelligence/exploited-this-month-2026-09/)**:
the monthly roundup of what CISA confirmed as exploited.

Latest analyses:

- [Citrix NetScaler zero-days: patch, then investigate](https://nulvex.com/research/cve/cve-2026-88771-citrix-netscaler-zero-days/) (CVE-2026-88771, CVE-2026-88772)
- [GitLab: an unauthenticated file read, so patch, then rotate secrets](https://nulvex.com/research/cve/cve-2026-85706-gitlab-unauthenticated-file-read/) (CVE-2026-85706)
- [N-central: pre-auth takeover of the server that manages every client](https://nulvex.com/research/cve/cve-2026-86218-n-able-n-central-pre-auth-rce/) (CVE-2026-86218)
- [ScreenConnect: a support session turned against the technician](https://nulvex.com/research/cve/cve-2026-84869-connectwise-screenconnect-host-file-execution/) (CVE-2026-84869)
- [MikroTrick: the 6.5 that takes over MikroTik routers](https://nulvex.com/research/cve/cve-2026-67279-mikrotik-routeros-mikrotrick-ssh-takeover/) (CVE-2026-67279)
- [WordPress core file inclusion: your theme and PHP settings decide the damage](https://nulvex.com/research/cve/cve-2026-87902-wordpress-page-template-file-inclusion/) (CVE-2026-87902)

Each rule in [nulvex-detections](https://github.com/Nulvex-Security/nulvex-detections#rule-index)
links back to the analysis that explains it.

### How we publish

- Every factual claim is traceable to a cited primary source or reproducible from evidence we
  hold. Where something is unknown, we say unknown.
- A detection rule says whether it has been tested against real telemetry. Most of ours have
  not been yet, and they say so.
- We publish what a defender needs. We do not publish working exploits for flaws that are
  still unpatched in the field.

### Contact

[contact@nulvex.com](mailto:contact@nulvex.com) · [nulvex.com](https://nulvex.com)
