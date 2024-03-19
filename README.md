<p align="center">
  <img src="https://github.com/rztprog/Dns-privacy-settings/assets/45171753/053cf1a2-5067-4e9d-b971-3fd0ca8cf06f" alt="Privacy firefox image" width="900"/>
</p>

# DNS PRIVACY SETTINGS

The idea came to me because often, the default DNS servers provided by our ISPs are unreliable, can block access to certain sites, and are not optimized for speed. That's why I suggest using two DNS servers simultaneously, along with their descriptions and instructions on how to set them up.

## 🔍 Want to go further?

If you want to explore further, you can check out my other complementary project, which focuses on [Firefox Privacy Extensions](https://github.com/rztprog/Firefox-privacy-extentions).

## 🌐 The 2 DNS Servers
<img src="https://github.com/rztprog/Dns-privacy-settings/assets/45171753/47c98889-5395-42ec-979d-90be12610666" alt="Privacy firefox image" width="200"/><br/>
Firstly, Quad9 ([official site](https://www.quad9.net/)) is recommended to be used as the root DNS resolver in Firefox due to its speed (ranked 7th according to [DNSPerf](https://www.dnsperf.com/#!dns-resolvers)), reliability, anonymity, free-of-charge nature, open-source, and its base in Switzerland.
<br/>
<br/>
<img src="https://github.com/rztprog/Dns-privacy-settings/assets/45171753/0ec26f2f-2ce1-45ff-a79d-631b3d7f792b" alt="Privacy firefox image" width="200"/><br/>
Secondly, UHB ([GitHub](https://github.com/Ultimate-Hosts-Blacklist/Ultimate.Hosts.Blacklist)) is to be integrated at the root of your Windows system. It functions similarly to modifying the HOSTS file to block certain sites. Its database is updated daily with new sites, thanks to a large number of lists compiled by domain experts.

## ⚙️ Setting up for Windows

## Step 1: Firefox

![firefoxdns](https://github.com/rztprog/Dns-privacy-settings/assets/45171753/95e14380-9a76-448a-8b27-08f074dd6a08)

1. Open Firefox.
2. Type in the address bar "about:preferences#privacy".
3. Scroll down to "Enable DNS over HTTPS using", check "Increased Protection".
4. In "Choose provider", select "Custom" and enter the following URL in the text field: "https://dns.quad9.net/dns-query".
5. Restart Firefox.

## Step 2: Windows

![windows1](https://github.com/rztprog/Dns-privacy-settings/assets/45171753/0628845a-5d61-4707-91a4-543a42202578)<br/>
![windows2](https://github.com/rztprog/Dns-privacy-settings/assets/45171753/07e00beb-b793-405b-adbd-079d4edf40fb)<br/>
![windows3](https://github.com/rztprog/Dns-privacy-settings/assets/45171753/8e572a6f-566f-4fac-b59c-99c2e8c0264a)<br/>
![windows4](https://github.com/rztprog/Dns-privacy-settings/assets/45171753/629f37ad-b6ab-47b7-82a8-21ee9c86a589)<br/>

1. Press the "WINDOWS + R" keys simultaneously to open the "Run" dialog.
2. Type "ncpa.cpl" in the text field and press Enter.
3. Right-click on your active network connection and select "Properties".
4. Double-click on "Internet Protocol Version 4 (IPv4)".
5. Check "Use the following DNS server addresses".
6. Enter "Preferred DNS server" as: 88.198.70.38.
7. Enter "Alternate DNS server" as: 88.198.70.39.
8. Click "OK".
9. Double-click on "Internet Protocol Version 6 (IPv6)".
10. Check "Use the following DNS server addresses".
11. Enter "Preferred DNS server" as: 2a01:4f8:140:5021::38.
12. Enter "Alternate DNS server" as: 2a01:4f8:140:5021::39.
13. Click "OK".
14. Restart your computer.
