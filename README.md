# Docker Pi-hole

# Start container

```sh
docker compose up -d
```

### Admin

http://localhost:7070/admin

### Adlists

https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts

https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/pro.plus.txt

## Popular Blocklists for Pi-hole

StevenBlack's Unified Hosts List:

URL: https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts

Description: A well-maintained blocklist that combines multiple reputable sources into one.
OISD Blocklist:

---

URL: https://dbl.oisd.nl/

Description: A comprehensive blocklist known for its effectiveness in blocking ads and trackers.

---
Energized Protection:

Basic: https://block.energized.pro/basic/formats/domains.txt

Unified: https://block.energized.pro/unified/formats/domains.txt

Description: Various lists tailored to different levels of blocking, from basic to comprehensive.

---

AdGuard DNS Filter:

URL: https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt

Description: A blocklist specifically designed for use with DNS-based ad blockers like Pi-hole.

---

1Hosts (Lite):

URL: https://raw.githubusercontent.com/badmojr/1Hosts/master/Lite/domains.txt

Description: A lightweight and efficient blocklist focused on blocking ads and trackers.

---

Dan Pollock's Hosts File:

URL: https://someonewhocares.org/hosts/hosts

Description: A well-known blocklist maintained by Dan Pollock, targeting ads and malicious domains.

---

Peter Lowe's Ad and Tracking Server List:

URL: https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext

Description: A frequently updated blocklist targeting ad servers and tracking domains.

---

Malware Domain List:

URL: https://www.malwaredomainlist.com/hostslist/hosts.txt

Description: A list focused on blocking domains known to distribute malware.

---

MVPS Hosts File:

URL: http://winhelp2002.mvps.org/hosts.txt

Description: A long-standing and trusted blocklist targeting ads, tracking, and other unwanted domains.
