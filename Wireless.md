# 📡 Wireless Networking

<br>

**MEANING:**

Consists of a way of communication using RF (Radio Frequency) waves instead of depending on physical cables.

It is also important to acknowledge that LAN, WAN, and MAN describe the scope or geographic area of a network, not whether it uses cables or wireless communication.

A LAN that uses Wi-Fi is called a WLAN (Wireless Local Area Network), while wireless versions of WAN and MAN are called WWAN (Wireless Wide Area Network) and WMAN (Wireless Metropolitan Area Network).

<br>

<img width="451" height="378" alt="WiredXWirelessExample" src="https://github.com/user-attachments/assets/4ce78a8a-e3de-4df4-bcd4-68601b4bb5e9" />

<sup>(A screenshot taken from Arash Deljoo's CCNA course on Udemy - Section 22)</sup>

<br>
<br>

## CONCEPTS AND TERMS

### Access Point (AP)

An **Access Point (AP)** in a wireless network allows devices to communicate with the network, acting as a transmitter and receiver.

### Independent Basic Service Set (IBSS)

An **Independent Basic Service Set (IBSS)**, also known as ad-hoc, allows devices such as tablets and phones to communicate directly with each other without an Access Point.

It can be used for direct and temporary connections between devices.

### Basic Service Set (BSS)

A **Basic Service Set (BSS)** is the fundamental building block of an IEEE 802.11 wireless local area network (WLAN), commonly known as Wi-Fi.

In a standard infrastructure BSS, a single Access Point (AP) acts as the central coordinator or base station, instead of no Access Point (AP) at all.

### Half-Duplex

Wi-Fi also usually operates mostly in half-duplex, instead of full-duplex like Ethernet over physical cables.

### SSID

**SSID (Service Set Identifier)** is basically the name of a Wi-Fi network that users see when they search for available wireless networks.

It identifies the wireless network that devices can connect to, such as `Home_WiFi` or `School_WiFi`.

### BSSID

**BSSID (Basic Service Set Identifier)** is an identifier used to identify a specific BSS.

In most Wi-Fi networks, it is the MAC address of the Access Point's wireless interface.

While the SSID can be the same for multiple Access Points, each BSSID is normally unique, allowing devices to distinguish between different APs.

For example, if a school has several Access Points all using the SSID `School_WiFi`, they can all provide the same wireless network while having different BSSIDs.

This allows a device to identify which specific AP it is currently connected to, even when multiple APs use the same SSID.

