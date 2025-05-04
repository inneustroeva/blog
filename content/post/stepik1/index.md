---
# Documentation: https://docs.hugoblox.com/managing-content/

title: "Stepik1"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2025-05-04T20:24:13+03:00
lastmod: 2025-05-04T20:24:13+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Hello everyone, I recently took a course in Computer science and today I want to leave a post about it. 
Today I'm going to talk about Online Security. 🖥💡☑️🔗🔐

# How the Internet works: The basics of the TCP/IP model

When you enter the URL in the browser (for example, yandex.ru ), the page is loaded due to the operation of network protocols. The Internet operates according to the TCP/IP model, which consists of four levels:

The application layer is responsible for the interaction of programs (browsers, mail) with the network. Examples of protocols: HTTP(S), FTP, SMTP.

Transport layer – provides data transfer between devices. Basic protocols:

TCP guarantees reliable delivery (used for web pages and mail).

UDP – provides speed, but without a guarantee of delivery (video calls, streams).

Network layer – routes data through IP addresses (IPv4 or IPv6), determining the path of packets between devices.

Link layer – transmits data physically (Ethernet, Wi-Fi).

# How is the request transmitted?
The browser sends the request through the application layer → TCP splits the data into segments → IP delivers it through routers to the server. The server processes the request and sends the response back along the same path.

DNS converts domain names (for example, yandex.ru ) to the IP address, and Traceroute helps to track the packet path.

# What are cookies and why are they needed?

Cookies are small data files that websites store in your browser for identification and personalization. They can be:

Session data is deleted after the browser is closed (for example, a shopping cart in an online store).

Permanent – they are stored longer so that you don't have to enter your username/password every time.

Third-party (third-party) – used by advertising services to track activities on different sites.

Pros: authorization without re-entering data, saving settings (language, shopping cart).
Cons: data collection for targeted advertising, risks of leakage (for example, in public Wi-Fi).

Tip: you can disable third—party cookies in the browser settings - this will increase privacy without loss of convenience.

# How does Tor work for online anonymity?

Tor (The Onion Router) is a browser that provides anonymity through onion routing. Your traffic passes through 3 random nodes:

The security node knows your IP, but not the destination address.

The intermediate node does not see either the sender or the recipient.

The exit node knows the site's address, but not your IP.

Each data layer is encrypted separately (like an onion peel). The speed is lower, but the traffic is anonymous. The output IP is changing (it can be in any country).

Important: Tor does not guarantee 100% anonymity, but it hides your location. In some countries, its nodes are prohibited.

# Wi-Fi Security: how to protect your network

Wi-Fi works according to IEEE 802.11 standards (for example, 802.11ac, 802.11ac). Encryption protocols are used to protect data.:

WEP is outdated (unreliable, weak 40–bit key).

WPA/WPA2 is safer (AES encryption, 128+ bit key).

WPA3 is the most modern (protects even weak passwords).

Authentication modes:

Personal – by password (for home).

Enterprise – through the user base (for companies).

Tip: Use WPA 3 and complex passwords. Disable WEP – it is vulnerable to hacking.
