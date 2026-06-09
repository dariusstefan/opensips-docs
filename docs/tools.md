---
title: OpenSIPS Tools
description: >-
  This list contains a few tools which can be used in setting up or testing your
  OpenSIPS installation.
---
## ngrep

```bash

### capture all SIP packages on 5060 on all interfaces
ngrep -W byline -td any . port 5060

### capture all SIP packages containing 'username' on port 5060 on all interfaces
ngrep -W byline -tqd any username port 5060

```

---

## tshark

```bash

### Filter on RTCP packets reporting any packet loss or jitter over 30ms:
tshark -i eth0 -o "rtcp.heuristic_rtcp: TRUE" -R 'rtcp.ssrc.fraction >= 1 or rtcp.ssrc.jitter >= 30' -V

### View a remote realtime capture with a local wireshark:
wireshark -k -i <(ssh -l root 192.168.10.98 tshark -w - not tcp port 22)
```
