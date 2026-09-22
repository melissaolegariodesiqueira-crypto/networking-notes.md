# 📡 Wireless Networking

> Notes about wireless networking concepts, standards, technologies, and security.

---

## 📚 Wireless Standards

### Wi-Fi Standards

| Standard | Frequency | Max. theoretical speed |
|---|---|---:|
| **802.11n (Wi-Fi 4)** | 2.4 / 5 GHz | 600 Mbps |
| **802.11ac (Wi-Fi 5)** | 5 GHz | 6.9 Gbps |
| **802.11ax (Wi-Fi 6)** | 2.4 / 5 / 6 GHz | 9.6 Gbps |

> [!NOTE]
> These are theoretical maximum speeds. Real-world performance is usually lower.

---

## 📶 Frequency Bands

### 2.4 GHz

- Longer range
- Better penetration through walls
- More interference
- Fewer non-overlapping channels

### 5 GHz

- Higher potential speeds
- More available channels
- Shorter range than 2.4 GHz
- More affected by walls

---

## 🔐 Wireless Security

Common wireless security standards include:

- **WPA**
- **WPA2**
- **WPA3**

> [!IMPORTANT]
> WPA3 provides stronger security than WPA2 when supported by the devices.

---

## 🛠️ Troubleshooting

### Common problems

1. Check whether the client is connected to the correct SSID.
2. Verify signal strength.
3. Check for interference.
4. Verify IP configuration.
5. Test connectivity with `ping`.

### Useful commands

```text
ipconfig
ping 192.168.1.1
```

---

## 🧠 Key Concepts

| Concept | Description |
|---|---|
| **SSID** | Name of a wireless network |
| **BSSID** | MAC address identifying a specific AP/radio |
| **AP** | Access Point |
| **WLAN** | Wireless Local Area Network |

---

## 📌 Quick Review

> **2.4 GHz →** longer range, more interference  
> **5 GHz →** higher speeds, shorter range  
> **WPA3 →** modern wireless security
