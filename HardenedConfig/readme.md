# ⚠️ Hardened Config
> Disclaimer this will block a LOT of stuff and may not be usuable out of the box. Monitor at the start and create allows by exception

This by default will include EVERY control on NextDNS as of 17/11/24 with some exceptions:  

# Block TLDs

All TLDs have been blocked except:
.au
.co
.com
.de
.edu
.fr
.gov
.info
.io
.live
.net
.uk

# Blocklists

All Blocklists except:

- No Google
- No Facebook

# Parental Control

All apps except:
- Facebook
- Amazon
- Spotify
- Signal
- ebay
- whatsapp
- messenger
- youtube (we will force restricted mode here instead)
- reddit


# Categories

All enabled except
- Video Streaming


# Deny List
This is empty by default but I have added here
> These have been taken from: https://github.com/jkerai1/SoftwareCertificates/tree/main/Bulk-IOC-CSVs
- some common vpns used to bypass controls such as nordvpn, expressvpn, mulladvpn
- Cryptocurrency domains
- remote desktop domains, to prevent scammers from initiating control over user's device
- 3rd party browsers as this is potential bypass  

Strong recommendation to use DNS over TLS with logging to create allows by exception

