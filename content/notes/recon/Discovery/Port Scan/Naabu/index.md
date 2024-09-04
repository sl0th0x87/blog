---
title: Naabu
weight: 200
menu:
  notes:
    name: Naabu
    identifier: notes-port-scan-naabu
    parent: notes-recon-discovery-port-scan
    weight: 20
---

<!-- Naabu Port Scan with JSON output -->
{{< note title="Naabu Port Scan with JSON output" >}}

```bash
cat hosts-up | naabu -p 80,443 -json -o open-ports
```

{{< /note >}}