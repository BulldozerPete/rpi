
## *PiHole*, Blokada, Diversion, PersonalDNSfilter, pfBlockerNG und PersonalBlocklist [Blocklisten](https://github.com/Zelo72/rpi/tree/master/pihole/blocklists) (Domain-Format)
***Weitere Formate: [Hosts](https://github.com/Zelo72/hosts) | [AdGuard/AdBlock](https://github.com/Zelo72/adguard)***

### ***DNS-Sperrlisten*** (Black-/Blocklists)

#### Gesamtliste ***(Empfehlung)***

[**Big**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/big.txt) - Zelo's "Big" Blockliste: ***Werbung, Fake, Tracking, Phishing, Malware, Coins und sonstiger "Mist" aus dem Netz***. Eine All-in-One Blockliste die keine zwingend benötigten "Funktionen" blockiert - kein striktes Blocken. Dead-Hosts (Hosts-Adressen die nicht mehr existieren) wurden aus dieser Liste entfernt. Sie kann als alleinige Blockliste verwendet werden. 

> ***Link:***
> https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/big.txt
> 
> ***Quellen:*** [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/big.stats)

**Die Big-Liste enthält die folgendn Listen:** ***[Multi](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/multi.txt) + [Fake](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/fake.txt) + [OISD Full](https://dbl.oisd.nl/)***

#### Basislisten (in Big enthalten)

[**Multi**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/multi.txt) - Zelo's "persönliche" Blockliste: ***Werbung, Tracking, Phishing, Malware, Coins und sonstiger "Mist" aus dem Netz***. Die **Light-Version der Big-Liste**. Eine Light-All-in-One Blockliste die keine zwingend benötigten "Funktionen" blockiert - kein striktes Blocken. Dead-Hosts (Hosts-Adressen die nicht mehr existieren) wurden aus dieser Liste entfernt. Sie kann als alleinige Blockliste verwendet werden.

> ***Link:***
> https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/multi.txt
> 
> ***Quellen:*** [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/multi.stats)

[**Fake**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/fake.txt) - Zelo's "anti Abzock" Blockliste: ***Fake-Shops, -Streaming, Abzocke und Co***. Auf Basis verschiedener Verbaucherseiten, Warnungen und anderen Fake-Listen. Als empfohlener Zusatz zur Multi-Blockliste, die Domains aus der Fakeliste sind nicht in der Multiliste enthalten.

> ***Link:*** https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/fake.txt
> 
> ***Quellen:*** *Verbraucherzentralen, Trusted Shops, Watchlist Internet, zelo72* - [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/fake.stats)

#### Erweiterungslisten (bei Bedarf - als Erweiterung zur Big- oder Multi-Liste)

[**Affiliate&Tracking**](https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/affiliatetracking.txt) - Zelo's "Affiliate & Tracking" Blockliste: ***Blockt Affiliate, Analytics & Tracking Links***.  **Hinweis:** Durch diese Blockliste werden Z.B. auch Links, die in der Google-Suche als Anzeige markiert sind oder Affiliate-Links in Mailangeboten, geblockt. ***(Optional - als Erweiterung zur Multiliste)***  

> ***Link:*** https://raw.githubusercontent.com/Zelo72/rpi/master/pihole/blocklists/affiliatetracking.txt
> 
> ***Quelle:*** [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/affiliatetracking.stats)

---

### ***Hinweis***

***Die Blocklisten wurden zur rein persönlichen, privaten Nutzung erstellt. Die Blocklisten wurden aus vorhandenen Quellen und eigenen Blacklisten unter Berücksichtigung von Whitelisten wie Dead-Hosts (Hosts-Adressen die nicht mehr existieren) und Toplisten (DE:Top 50 - Welt:Top 50) zusammen gestellt.***

**Die Blocklisten werden täglich aktualisiert.**

---






