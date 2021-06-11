
## *PiHole*, Blokada, Diversion, PersonalDNSfilter, pfBlockerNG und PersonalBlocklist [Blocklisten](https://github.com/Zelo72/rpi/tree/master/pihole/blocklists) (Domain-Format)
***Weitere Formate: [Hosts](https://github.com/Zelo72/hosts) | [AdGuard/AdBlock](https://github.com/Zelo72/adguard)***

### ***DNS-Sperrlisten*** (Black-/Blocklists)

#### Basislisten (empfohlen)

[**Multi**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/multi.txt) - Zelo's "persönliche" Blockliste: ***Werbung, Tracking, Phishing, Malware, Coins und sonstiger "Mist" aus dem Netz***. Eine All-in-One Blockliste die keine zwingend benötigten "Funktionen" blockiert - kein striktes Blocken. Dead-Hosts (Hosts-Adressen die nicht mehr existieren) wurden aus dieser Liste entfernt. Sie kann als alleinige Blockliste verwendet werden und nach Wunsch durch Hinzufügen der Erweiterungslisten (siehe unten) erweitert werden. ***(Empfehlung)***  

> ***Link:***
> https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/multi.txt
> 
> ***Quellen:*** [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/multi.stats)

[**Fake**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/fake.txt) - Zelo's "anti Abzock" Blockliste: ***Fake-Shops, -Streaming, Abzocke und Co***. Auf Basis verschiedener Verbaucherseiten, Warnungen und anderen Fake-Listen. Als empfohlener Zusatz zur Multi-Blockliste, die Domains aus der Fakeliste sind nicht in der Multiliste enthalten. ***(Empfehlung)***  

> ***Link:*** https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/fake.txt
> 
> ***Quellen:*** *Verbraucherzentralen, Trusted Shops, Watchlist Internet, zelo72* - [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/fake.stats)

#### Erweiterungslisten (bei Bedarf - als Erweiterung zur Multi-Liste)

[**Privacy**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/privacy.txt) - Zelo's "Privacy" Blockliste: ***Blockt Telemetrie & Metriken von Endgeräten, Diensten und Systemen diverser Hersteller (OEM)***. ***(Optional - als Erweiterung zur Multiliste)***  

> ***Link:*** https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/privacy.txt
> 
> ***Quelle:*** *zelo72*

[**Affiliate&Tracking**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/affiliatetracking.txt) - Zelo's "Affiliate & Tracking" Blockliste: ***Blockt Affiliate, Analytics & Tracking Links***.  **Hinweis:** Durch diese Blockliste werden Z.B. auch Links, die in der Google-Suche als Anzeige markiert sind oder Affiliate-Links in Mailangeboten, geblockt. ***(Optional - als Erweiterung zur Multiliste)***  

> ***Link:*** https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/affiliatetracking.txt
> 
> ***Quelle:*** [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/affiliatetracking.stats)

### ***RegEx-Filter*** (Nur für erfahrene Anwender empfohlen!)

[**RegEx**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/regex/regex_filter.txt) - Zelo's "RegEx" Blacklist: ***Filtert mögliche Ads- und Tracking-Domains mittels regulären Ausdrücken***. RegEx-Ausdrücke (Inhalt der TXT-Datei) können per Copy & Paste in Pihole unter *Blacklist > RegEX filter > Regular Expression* hinzugefügt werden. ***(Nur erfahrene Anwender)***  

**Weitere RegEx-Filter wie z.B. Geo-Blocking sind [hier](https://github.com/Zelo72/rpi/tree/master/pihole/regex) zu finden.**
> ***Quelle:*** *zelo72*

---

### ***DNS-Freigabeliste*** (Whitelist)

[**White**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/white.list) - Zelo's Whitelist: ***Domains die man nicht blocken sollte***. Die in der Whitelist aufgeführten Domains wurden **gegen die Multi- und Fake-Blockiste geprüft und sind in diesen Blocklisten nicht mehr enthalten**.

> ***Quelle:*** *zelo72*

---

### ***DNS-Sperrlisten*** (Black-/Blocklists) - generiert aus bekannten Anbieterlisten

**In das Domain-Format umgewandelte Listen** + WWW- & third-party/popup Domains.

***Folgende Listen sind bereits in der Multi-Liste enthalten!***

[**EasyList**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/easylist.txt) - EasyList (+Germany) & EasyList Privacy + Erweiterung um mögliche WWW-Domains. ***(in Multi enthalten)*** - Quelle: [EasyList](https://easylist.to/) - [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/easylist.stats)

[**PrigentAds**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/prigentads.txt) - Blacklists UT1 von Fabrice Prigent: Prigent-Ads + Erweiterung um mögliche WWW-Domains. ***(in Multi enthalten)*** - Quelle: [Blacklists Université Toulouse 1 Capitole](https://dsi.ut-capitole.fr/blacklists/index_en.php) - [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/prigentads.stats)

[**AdguardDNS**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/adguarddns.txt) - AdGuard DNS Filterliste (AdGuard Base filter, German + English filter, Social media filter, Tracking Protection filter, Mobile Ads filter, EasyList and EasyPrivacy) + Erweiterung um mögliche WWW-Domains. ***(in Multi enthalten)*** - Quelle: [AdguardDNS](https://github.com/AdguardTeam) - [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/adguarddns.stats)

[**NextDNS**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/nextdns.txt) - NextDNS + Affiliate & Tracking + Erweiterung um mögliche WWW-Domains (Eine umfassende Blockliste zum Blockieren von Anzeigen & Trackern in allen Ländern. Dies ist die empfohlene Starterblockliste von NextDNS. ***(in Multi enthalten)*** - Quelle: [NextDNS](https://github.com/nextdns) - [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/nextdns.stats)

---

### ***DNS-Sperrlisten*** (Black-/Blocklists) - Sonstige

***Folgende Listen sind NICHT in der Multi-Liste enthalten!***

[**CryptoScamDB**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/cryptoscamdb.txt) - CryptoScamDB von https://cryptoscamdb.org/ umgewandelt + Erweiterung um mögliche WWW-Domains. Bereinigt von toten und falsch positiven Domains. **Trotz der Bereinigung kann die Liste falsch positve Domains enthalten!** - Quelle: [CryptoScamDB](https://api.cryptoscamdb.org/v1/blacklist) - [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/cryptoscamdb.stats)

---

### ***Hinweis***

***Die Blocklisten wurden zur rein persönlichen, privaten Nutzung erstellt. Die Blocklisten wurden aus vorhandenen Quellen und eigenen Blacklisten unter Berücksichtigung von Whitelisten wie Dead-Hosts (Hosts-Adressen die nicht mehr existieren) und Toplisten (DE:Top 50 - Welt:Top 50) zusammen gestellt.***

**Die Blocklisten werden täglich aktualisiert.**

---






