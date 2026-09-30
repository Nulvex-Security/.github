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
| [nulvex-detections](https://github.com/Nulvex-Security/nulvex-detections) | Sigma, Suricata and Wazuh rules. Each one states its expected telemetry, its false positives, and whether it has actually been tested |

More will follow as there is real content to put in it. We would rather have one useful
repository than five empty ones.

### Research

Vulnerability analysis written for the people who have to act on it: who is really exposed,
what to do, and what we could not establish. Published at
**[nulvex.com/research](https://nulvex.com/research)**.

Latest analyses:

- [MikroTrick: the 6.5 that takes over MikroTik routers](https://nulvex.com/research/cve/cve-2026-67279-mikrotik-routeros-mikrotrick-ssh-takeover/) (CVE-2026-67279)
- [WordPress core file inclusion: your theme and PHP settings decide the damage](https://nulvex.com/research/cve/cve-2026-87902-wordpress-page-template-file-inclusion/) (CVE-2026-87902)
- [StyleSmuggler: patching Magento is the easy part](https://nulvex.com/research/cve/cve-2026-75650-magento-stylesmuggler-template-injection/) (CVE-2026-75650)
- [PHP ext-pgsql: a 9.8 that only reaches four PostgreSQL helpers](https://nulvex.com/research/cve/cve-2026-17543-php-pgsql-backslash-sql-injection/) (CVE-2026-17543)
- [wp2shell: a stock WordPress site taken over with one anonymous request](https://nulvex.com/research/cve/cve-2026-63030-wordpress-wp2shell-batch-route-confusion/) (CVE-2026-63030)

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
