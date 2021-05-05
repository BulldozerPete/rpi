## [PiHole, Blokada, Diversion, PersonalDNSfilter, pfBlockerNG und PersonalBlocklist Blocklisten](https://github.com/Zelo72/rpi/tree/master/pihole/blocklists) (Domain-Format)

[**Multi**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/multi.txt) - Zelo's "persönliche" Domain-Blockliste: *Werbung, Tracking, Phishing, Malware, Coins und sonstiger "Mist" aus dem Netz*. Eine All-in-One Filterliste die keine zwingend benötigten "Funktionen" blockiert - kein striktes Blocken. Dead-Hosts (Hosts-Adressen die nicht mehr existieren) wurden aus dieser Liste entfernt. Sie kann als alleinige Pihole-Blockliste verwendet werden. ***(Empfehlung)*** *- ca. 372.000 Domains*

[**Fake**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/fake.txt) - Zelo's "anti Abzock" Domain-Blockliste: ***Fake-Shops, -Streaming, Abzocke und Co***. Auf Basis verschiedener Verbaucherseiten, Warnungen und anderen Fake-Listen. Als Zusatz zur Multi-Filterliste ***(Empfehlung)*** *- ca. 13.500 Domains*

---

[**Erweiterung**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/ext.txt) - Erweiterung zu Zelo's "persönlichen" Domain-Blockliste: *Erweiterung zur Multi- und Fake-Liste. Blockt zusätzliche Werbung, Tracking, Phishing, Malware, Coins und sonstigen "Mist" aus dem Netz*. Diese Liste enthält keine Domains aus der Multi- oder Fake-Liste. Sie sollte nur als Zusatz zu den zwei o.g. Listen verwendet werden. ***(Optinal)*** *- ca. 1.250.000 Domains*

---

**Aus dem AdBlock-Format ins Domain-Format umgewandelte Listen** + WWW- & third-party/popup Domains *(Listen sind in Multi/Erweiterung bereits enthalten)*

[**EasyList**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/easylist.txt) - EasyList (+Germany) & EasyList Privacy + Erweiterung um mögliche WWW-Domains. ***(in Multi enthalten)*** - Quelle: [EasyList](https://easylist.to/)

[**AdguardDNS**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/adguarddns.txt) - AdGuard DNS Filterliste (AdGuard Base filter, German + English Filter, Social media filter, Tracking Protection filter, Mobile Ads filter, EasyList and EasyPrivacy) + Erweiterung um mögliche WWW-Domains. ***(in Multi enthalten)*** - Quelle: [AdguardDNS](https://github.com/AdguardTeam)

[**NextDNS**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/nextdns.txt) - NextDNS empfohlen + Affiliate & Tracking + Erweiterung um mögliche WWW-Domains (Eine umfassende Blockliste zum Blockieren von Anzeigen & Trackern in allen Ländern. Dies ist die empfohlene Starterblockliste von NextDNS. ***(in Erweiterung enthalten)*** - Quelle: [NextDNS](https://github.com/nextdns)

---

***Die Blocklisten wurden zur rein persönlichen, privaten Nutzung estellt. Die Multi-, Erweiterungs- und Fake-Blockliste wurde aus [vorhandenen Quellen](https://github.com/Zelo72/rpi/tree/master/pihole/blocklists/quellen) und eigenen [Blacklisten](https://github.com/Zelo72/rpi/tree/master/pihole/blocklists/quellen) unter Berücksichtigung von Whitelisten, Dead-Hosts (Hosts-Adressen die nicht mehr existieren) und Alexa-Toplisten (DE:Top 100 - Welt:Top 100) zusammen gestellt.***

**Die Blocklisten werden täglich um 03:45 Uhr aktualisiert.**

---

*Die Blocklisten im Domain-Format lassen sich - neben PiHole - auch mit Blokada, Diversion, PersonalDNSfilter, pfBlockerNG und PersonalBlocklist nutzen.*
