# ⚠️ Hardened Config ⚠️
> Disclaimer this will block a LOT of stuff and may not be usuable out of the box. Monitor at the start and create allows by exception

This by default will include EVERY control on NextDNS as of 17/11/24 with some exceptions:  

❗Known Issue when importing configuration profiles involving parental controls  

# Block TLDs

All TLDs have been blocked except:

- .au
- .co
- .com
- .de
- .edu
- .fr
- .gov
- .info
- .io
- .live
- .ms
- .net
- .uk

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
- Ebay
- Whatsapp
- Messenger
- Youtube (we will force restricted mode here instead)
- Reddit


# Categories

All enabled except
- Video Streaming (Large portions of this category can be controlled by the other apps such as netflix, youtube, piracy)


# Deny List
This is empty by default but I have added here
- some common vpns used to bypass controls such as nordvpn, expressvpn, mulladvpn
- Cryptocurrency domains
- remote desktop domains (RMMs), to prevent scammers from initiating control over user's device
- 3rd party browsers as this is potential bypass  
> These have been taken from: https://github.com/jkerai1/SoftwareCertificates/tree/main/Bulk-IOC-CSVs  #


Strong recommendation to use DNS over TLS (or DNS over HTTPs if DNS over TLS is not an option) with logging to create allows by exception

# Clean Up - Manual  

## Remove the API key if you are not using it after the Import stage:  
> This can be done from Account and scrolling down to the bottom  
![image](https://github.com/user-attachments/assets/57325e82-4dd1-49ee-a889-ace8fbe3540a)


> 🗒️ Also Disclaimer that is a very long configuration file and can take some time to load⏲️  
