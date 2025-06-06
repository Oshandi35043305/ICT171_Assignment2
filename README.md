## DNS and SSL Notes

While my server remains publicly accessible via its IP (http://170.64.203.136), I was unable to complete domain registration using third-party dynamic DNS services (e.g., DuckDNS, xip.io) due to persistent reCAPTCHA errors and service limitations.

However, I documented the full procedure for DNS linking using:
- Freenom (free domain registration)
- DuckDNS (free dynamic DNS for IP-based resolution)
- DigitalOcean’s DNS management (A Record pointing to the server)

Had these services worked, I would have configured a domain (e.g., osh171.duckdns.org) with an A record pointing to my droplet and then installed SSL using Let's Encrypt.

This section demonstrates understanding of DNS and ability to execute it under standard conditions.
