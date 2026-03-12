![ShaunsPiHoleBlockList Banner](https://github.com/shaun9111/ShaunsPiHoleBlockList/blob/main/banner.jpg)

# 🌐 ShaunsPiHoleBlockList
### <span style="color:#4CAF50;">Created & Maintained by</span> shaun9111

---

## 🎯 Purpose
This blocklist is designed to complement—not replace—other well‑maintained and widely trusted ad‑blocking lists. For best results, use it alongside popular community lists such as:

- **StevenBlack Unified Hosts** — https://github.com/StevenBlack/hosts  
- **OISD Blocklist** — https://oisd.nl    
- **AdGuard DNS Filter** — https://github.com/AdguardTeam/AdGuardSDNSFilter  
- **uBlock Origin Filters** — https://github.com/uBlockOrigin/uAssets  

These lists provide broad coverage, while ShaunsPiHoleBlockList focuses specifically on analytics, tracking, and anti‑adblock detection domains.

This list targets:
- Ad Networks such as Google Ads, DoubleClick, and Meta Ads.
- Tracking & Analytics including fingerprinting, cross‑device ID systems, and telemetry.
- Adblock Detectors used by websites to detect Pi‑hole or browser‑based ad blockers.

---

## 📥 Blocklist URL
Paste this URL directly into Pi‑hole under:
Group Management → Adlists → Add a new adlist

https://github.com/shaun9111/ShaunsPiHoleBlockList/blob/main/app-analytics-ADS.txt

## 📁 How to Use This Blocklist

### Pi‑hole
1. Copy the blocklist URL from the section above.  
2. Go to Pi‑hole Admin → Group Management → Adlists.  
3. Paste the URL.  
4. Click Add.  
5. Update gravity.

### AdGuard Home
1. Copy the same URL.  
2. Go to Filters → DNS Blocklists.  
3. Add a new custom list and paste the URL.  
4. Save and refresh filters.

---

## 🧪 Compatibility
This blocklist works with:
- Pi‑hole  
- AdGuard Home  
- NextDNS (custom blocklist import)  
- pfSense / OPNsense DNSBL  
- Any DNS filtering system that accepts plain‑text domain lists  

---

## 📝 Notes
- This list does not include cosmetic filtering (browser‑side only).  
- Some websites use inline JavaScript detection that DNS blocking cannot bypass.  
- For maximum protection, combine this list with uBlock Origin or AdGuard in your browser.

---

## 🤝 Contributing
Contributions, domain submissions, and improvements are welcome.  
Open an issue or submit a pull request to help strengthen the list.

---

## 📜 License
Released under the MIT License — free to use
