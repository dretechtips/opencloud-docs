# opencloud[WIP]
A free and open source self-hosted office solution for small businesses and people who are privacy conscious. Installs on a single server machine with step by step procedures on how to properly setup the solution.

## Why was this created? / Goals
- [X] Privacy - Move your data away from centralized servers and privacy invasive practices such as the [Third-Party Doctrine](https://en.wikipedia.org/wiki/Third-party_doctrine).
- [X] Security - Modern security practices with a reverse proxy implementation to mascurate true IP Address and protect against DDOS attacks.
- [X] Ease of Use - Simple installation guide with LDAP based universal account management. 
- [X] Open Ecosystem - Easy interoperability with other components that support LDAP based accounts.

## Recommended/Pre-bundled Components
- [X] [TrueNAS](https://www.truenas.com/) - Base OS and Storage Manager
- [X] [Nextcloud](https://nextcloud.com/) - Office Suite & File Sync
- [X] [iRedMail](https://iredmail.org/) - E-mail Solution
- [X] [Adguard DNS](https://adguard.com/en/adguard-home/overview.html) - Network-wide Adblocker
- [X] [CUPS](https://www.cups.org/) - Printer Manager
- [X] [Apache Directory Service](https://directory.apache.org/) + opencloud-acm - Account Management
- [X] [Nginx](https://www.nginx.com/) + [ufw](https://help.ubuntu.com/community/UFW) - External Network Security


