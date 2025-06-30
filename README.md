# 📡 Task 5 – Capture and Analyze Network Traffic Using Wireshark

**Objective:**  
Capture live network packets and identify basic protocols and traffic types using Wireshark.

## 🛠 Tools Used

- **Wireshark** (Packet analysis tool)
- **Command Prompt / Terminal** (For generating traffic via ping, web browsing)

---

## 📁 Files Included

| File/Folder         | Description                                          |
|---------------------|------------------------------------------------------|
| `capture/network-capture-task5.pcap` | The raw packet capture file (PCAP)      |
| `report/report.md`  | Summary report of protocols identified and details   |
| `screenshots/*.png` | (Optional) Screenshots of filters and packet views   |

---

## 📊 Protocols Identified

| Protocol | Description                          | Use Case Example              |
|----------|--------------------------------------|-------------------------------|
| DNS      | Domain Name System                   | Resolved `google.com`         |
| TCP      | Transmission Control Protocol        | Used in HTTP and general comm |
| HTTP     | HyperText Transfer Protocol          | Browsing `example.com` site   |

---

## 🔍 Steps Performed

1. Installed Wireshark.
2. Captured live traffic on active network.
3. Generated traffic by pinging `google.com` and browsing a website.
4. Stopped capture after 1 minute.
5. Applied filters (`http`, `dns`, `tcp`) to analyze traffic.
6. Exported `.pcap` and summarized the findings in the report.

---

**Protocols Identified:**
1. DNS – Used for resolving domain names like google.com.
2. TCP – Found in multiple packets as base protocol.
3. HTTP – Observed while browsing a website.

**Details:**
- DNS packets showed queries to domains like `google.com`.
- HTTP packets showed requests to `example.com` and status codes.
- TCP used in multiple communication sessions. 

## 📸 Screenshots (Optional)

Add screenshots of Wireshark interface with:
- Filtered views (`http`, `dns`)
- Example packet details
