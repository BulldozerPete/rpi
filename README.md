## *PiHole*, Blokada, Diversion, PersonalDNSfilter, pfBlockerNG und PersonalBlocklist [Blocklisten](https://github.com/Zelo72/rpi/tree/master/pihole/blocklists) (Domain-Format)

### ***DNS-Sperrlisten*** (Blacklists)

#### Moderates Blocking ~10.000 Domains

[**AdsTrk**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/adstrk.txt) - Zelo's "Ads & Tracking" Blockliste: ***Werbung, Tracking - nur das Nötigste***. Eine ***Light*** Filterliste die nur Werbung und Tracking blockt - Optimiert fuer den deutschsprachigen Raum. Die Filterliste wird stetig erweitert. Alle Filter sind in ***Multi*** enthalten. *(Optional)*  

> ***Quelle:*** *zelo72*

#### Normales Blocking (Empfohlen) ~330.000 Domains

[**Multi**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/multi.txt) - Zelo's "persönliche" Blockliste: ***Werbung, Tracking, Phishing, Malware, Coins und sonstiger "Mist" aus dem Netz***. Eine All-in-One Filterliste die keine zwingend benötigten "Funktionen" blockiert - kein striktes Blocken. Dead-Hosts (Hosts-Adressen die nicht mehr existieren) wurden aus dieser Liste entfernt. Sie kann als alleinige Blockliste verwendet werden. ***(Empfehlung)***  

> ***Quellen:*** *adaway.org, adguard.com, d3ward, easylist.to, fademind, firebog, hoshsadiq, jkrejcha, laicure, nextdns, notracking, oisd.nl, phishing.army,   prigentads, shallalist, someonewhocares.org, spam404, stevenblack, urlhaus.abuse.ch, yhonay, yoyo.org, zerodot1, zelo72*  

[**Fake**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/fake.txt) - Zelo's "anti Abzock" Blockliste: ***Fake-Shops, -Streaming, Abzocke und Co***. Auf Basis verschiedener Verbaucherseiten, Warnungen und anderen Fake-Listen. Als Zusatz zur Multi-Filterliste ***(Empfehlung)***  

> ***Quellen:*** *Verbraucherzentralen, Trusted Shops, Watchlist Internet, zelo72*

#### Weitreichendes Blocking ~1.300.000 Domains
  
[**Extended**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/ext.txt) - Erweiterte Blockliste: ***Enthält alles aus der Multi- und Fake-Liste und blockt zusätzliche Werbung, Tracking, Phishing, Malware, Scam, Coins und sonstigen "Mist" aus dem Netz***. Sie kann als alleinige Pihole-Blockliste verwendet werden. *(Optional - die volle Dröhnung!)*  

> ***Quellen:*** *adaway.org, adguard.com, cyberthreatcoalition.org, d3ward, dandelionsprout, easylist.to, fademind, firebog, hoshsadiq, jkrejcha, laicure, nextdns, notracking, oisd.nl, osint.digitalside.it, phishing.army, prigentads, shallalist, someonewhocares.org, spam404, stevenblack, urlhaus.abuse.ch, yhonay, yoyo.org, zerodot1, zelo72*

---

### ***DNS-Sperrlisten*** (Blacklists) - generiert aus Anbieterlisten

**In das Domain-Format umgewandelte Listen** + WWW- & third-party/popup Domains *(Listen in der Multi-/Extended-Liste bereits enthalten)*

[**EasyList**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/easylist.txt) - EasyList (+Germany) & EasyList Privacy + Erweiterung um mögliche WWW-Domains. ***(in Multi enthalten)*** - Quelle: [EasyList](https://easylist.to/)

[**PrigentAds**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/prigentads.txt) - Blacklists UT1 von Fabrice Prigent: Prigent-Ads + Erweiterung um mögliche WWW-Domains. ***(in Multi enthalten)*** - Quelle: [Blacklists Université Toulouse 1 Capitole](https://dsi.ut-capitole.fr/blacklists/index_en.php)

[**AdguardDNS**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/adguarddns.txt) - AdGuard DNS Filterliste (AdGuard Base filter, German + English filter, Social media filter, Tracking Protection filter, Mobile Ads filter, EasyList and EasyPrivacy) + Erweiterung um mögliche WWW-Domains. ***(in Multi enthalten)*** - Quelle: [AdguardDNS](https://github.com/AdguardTeam)

[**NextDNS**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/nextdns.txt) - NextDNS + Affiliate & Tracking + Erweiterung um mögliche WWW-Domains (Eine umfassende Blockliste zum Blockieren von Anzeigen & Trackern in allen Ländern. Dies ist die empfohlene Starterblockliste von NextDNS. ***(in Extended enthalten)*** - Quelle: [NextDNS](https://github.com/nextdns)

---

### ***Hinweis***

***Die Blocklisten wurden zur rein persönlichen, privaten Nutzung erstellt. Die Multi-, Extended- und Fake-Blockliste wurde aus [vorhandenen Quellen](https://github.com/Zelo72/rpi/tree/master/pihole/blocklists/quellen) und eigenen [Blacklisten](https://github.com/Zelo72/rpi/tree/master/pihole/blocklists/quellen) unter Berücksichtigung von Whitelisten wie Dead-Hosts (Hosts-Adressen die nicht mehr existieren) und [Toplisten](https://github.com/Zelo72/rpi/tree/master/toplists) (DE:Top 50 - Welt:Top 50) zusammen gestellt.***

**Die Blocklisten werden täglich aktualisiert.**

---

*Die Blocklisten im Domain-Format lassen sich - neben PiHole - auch mit Blokada, Diversion, PersonalDNSfilter, pfBlockerNG und PersonalBlocklist nutzen.* ![grafik](https://user-images.githubusercontent.com/62211544/117189136-22048a80-adde-11eb-933d-6e4159fc47d9.png)![grafik](https://user-images.githubusercontent.com/62211544/117189274-4a8c8480-adde-11eb-9d58-b035a211dbdc.png)![grafik](https://user-images.githubusercontent.com/62211544/117189305-55dfb000-adde-11eb-978d-de741fc269a6.png)![grafik](https://user-images.githubusercontent.com/62211544/117189369-6b54da00-adde-11eb-97bd-7ef01a33b12a.png)![grafik](https://user-images.githubusercontent.com/62211544/117189399-7445ab80-adde-11eb-8ab5-d7aeb652269e.png)![grafik](https://user-images.githubusercontent.com/62211544/117189443-7f004080-adde-11eb-99f3-a73c943bf5e1.png)

---
