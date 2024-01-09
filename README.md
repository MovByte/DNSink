# DNSink

## Prolouge

The oldest surviving Sinkhole DNS.

## The future

- The drawback of DNS exploits is that they must always be updated when CDNs or APIs (when redirection is used). DNS and CA Stores modification isn't always available. This will be fixed by automation thorugh [Filter Watchdog](https://github.com/VyperGroup/FilterWatchdog).
- Eventually, this will be ported to ADGuard. I will make a DNSMasq to ADGuard converter in Rust

## How to run

The DNS IP: **192.198.95.86**
If the dns is blocked, use vpn

### Chrome OS

1. Edit Wi-Fi connection
2. Click on Network
3. Click on Nameservers
4. Choose Custom Nameservers
5. Add the IP address
6. Restart

> You can import [the ONC file](./userConfs/DNSink.onc) for ChromeOS in chrome://network if your workplace blocks chrome://settings

### Windows

1. Open Settings
2. Click Network & Internet
3. Click on Wi-Fi
4. Click view additional properties
5. Click Edit on on IPv4 Dns Servers
6. Add the IP

## Objectives

- This DNS redirects Filter Software, TV-based Spyware and Adware, Managed Chromebook CDNs
- Certain CDN takeover attacks are performed with it in addition to a CA Server. When using DNS Takeover, the servers will feed false data to make the spyware company think that you are using their services "properly."
- Network profiles are provided for devices which have network policies

## Credits

Made by [EV](https://github.com/MovByte) hosted by emmaknijn (on Discord)
