---
title: Nmap
weight: 100
menu:
  notes:
    name: Nmap
    identifier: notes-port-scan-nmap
    parent: notes-recon-discovery-port-scan
    weight: 10
---

<!-- Nmap Host Discovery -->
{{< note title="Nmap Host Discovery" >}}

```bash
nmap -v -oA nmap/all-hosts 10.10.0.0/24
```

{{< /note >}}

<!-- Nmap Port Scan and OS/Version detection -->
{{< note title="Nmap Port Scan and OS/Version detection" >}}

```bash
nmap -v -sV -O -p- -oA nmap/all-ports -iL hosts-up
```

{{< /note >}}