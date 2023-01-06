## Providers

| Name                  | Filtered? | Source Link                                 | Anycast? | Install                                                                                                                                                                                                                                          |
| --------------------- | --------- | ------------------------------------------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Adguard - Default     | Yah       | https://adguard-dns.io/en/public-dns.html   | Yah      | [HTTPS](https://github.com/Undercook1799/layer7-dns-profiles/raw/master/profiles/adguard-default-https.mobileconfig), [TLS](https://github.com/Undercook1799/layer7-dns-profiles/raw/master/profiles/adguard-default-tls.mobileconfig)           |
| Adguard - Family      | Yah       | https://adguard-dns.io/en/public-dns.html   | Yah      | [HTTPS](https://github.com/Undercook1799/layer7-dns-profiles/raw/master/profiles/adguard-family-https.mobileconfig), [TLS](https://github.com/Undercook1799/layer7-dns-profiles/raw/master/profiles/adguard-family-tls.mobileconfig)             |
| Adguard - Unfiltered  | Nah       | https://adguard-dns.io/en/public-dns.html   | Yah      | [HTTPS](https://github.com/Undercook1799/layer7-dns-profiles/raw/master/profiles/adguard-nonfiltering-https.mobileconfig), [TLS](https://github.com/Undercook1799/layer7-dns-profiles/raw/master/profiles/adguard-nonfiltering-tls.mobileconfig) |
| Blahdns - Germany     | Yah       | https://blahdns.com/                        | Nah      | [HTTPS](https://github.com/Undercook1799/layer7-dns-profiles/raw/master/profiles/blahdns-germany-https.mobileconfig), [TLS](https://github.com/Undercook1799/layer7-dns-profiles/raw/master/profiles/blahdns-germany-tls.mobileconfig)           |
| Blahdns - Japan       | Yah       | https://blahdns.com/                        | Nah      | [HTTPS](https://github.com/Undercook1799/layer7-dns-profiles/raw/master/profiles/blahdns-japan-https.mobileconfig), [TLS](https://github.com/Undercook1799/layer7-dns-profiles/raw/master/profiles/blahdns-japan-tls.mobileconfig)               |
| Blahdns - Switzerland | Yah       | https://blahdns.com/                        | Nah      | [HTTPS](https://github.com/Undercook1799/layer7-dns-profiles/raw/master/profiles/blahdns-switzerland-https.mobileconfig), [TLS](https://github.com/Undercook1799/layer7-dns-profiles/raw/master/profiles/blahdns-switzerland-tls.mobileconfig)   |
| Blahdns - Singapore   | Yah       | https://blahdns.com/                        | Nah      | [HTTPS](https://github.com/Undercook1799/layer7-dns-profiles/raw/master/profiles/blahdns-singapore-https.mobileconfig), [TLS](https://github.com/Undercook1799/layer7-dns-profiles/raw/master/profiles/blahdns-singapore-tls.mobileconfig)       |
| DNS.SB                | Nah       | https://dns.sb/doh/ and https://dns.sb/dot/ | Yah      | [HTTPS](https://github.com/Undercook1799/layer7-dns-profiles/blob/master/profiles/DNS.SB-https.mobileconfig), [TLS](https://github.com/Undercook1799/layer7-dns-profiles/blob/master/profiles/DNS.SB-tls.mobileconfig)                           |
| Njalla                | Nah       | https://dns.njal.la/                        | Nah      | [HTTPS](https://github.com/Undercook1799/layer7-dns-profiles/raw/master/profiles/njalla-https.mobileconfig), [TLS](https://github.com/Undercook1799/layer7-dns-profiles/raw/master/profiles/njalla-tls.mobileconfig)                             |

## Installation Guide

For **iOS**
Seek a DNS provider from the list and click either HTTPS or TLS using Safari and click allow when given a prompt that states "XXXX." The profile will now install.

For **MacOS**

## Contributing a new profile

Profiles are basically text files. Copy the template and change the things with !!!, IP addresses, and be sure to change its UUID, for example, by generating a new one ["online (V4)"](https://www.uuidgenerator.net/). Make sure you update the README with the new profile's info. Or you can create an "issue" in this repository with the link to the DNS provider that you would like to be added.

#### Notes:

- This was forked from Paul Miller's repo: https://github.com/paulmillr/encrypted-dns
- DoH ("DNS over HTTPS) will run your queries over port 443; DoT ("DNS over TLS") will run your queries over port 853. Note that DNS runs over port 53 by default.
- None of these profiles are signed xoxo
- Not going to lie, but I have minimal idea of how to operate Github
