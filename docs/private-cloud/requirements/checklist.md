---
sidebar_position: 2
---

# Checklist

Summary of things to do before setup.

## Things to do

1. Make sure the server is connected to fiber internet (e.g. **MAXIS**, **UNIFI**, **TIME**).
:::caution Notes
**STRICTLY NO STREAMYX/BROADBAND/UNIFI LITE ARE ALLOWED**
:::
2. Prepare a clean server with at least minimum spec below:
    - **CPU**: Intel i5 (5th gen) & above or AMD Ryzen 5 & above
    - **RAM**: 8 GB
    - **Disk**: Solid state drive (SSD)
3. Reserve **two** local IP Address:
    - Windows
    - Debian virtual machine
    - If no special requirements, may leave it empty in the checklist. We will assign them accordingly.
4. Port forwarding will be point towards the **Debian virtual machine**. So configure your port forward on the debian IP address reserved above.
    - If not sure how to configure this, may leave it empty in the checklist. We will help in configuring it.
5. Enable virtualization in the BIOS. Here's how you can check if you have enabled it.
    - If it is not enabled, you may need to enter BIOS to switch it on. [Guide on how to enter BIOS](https://www.laptopmag.com/articles/access-bios-windows-10)

6. Enable Hyper-V after the above has been done.
    - [Guide on how to enable Hyper-V Manager](https://www.nextofwindows.com/how-to-enable-configure-and-use-hyper-v-on-windows-10)

7. Get **Dynamic DNS (DDNS)/ Fixed WAN IP** ready.
    - If you are getting one from *NO-IP*, you may set it up using the client provided. [NO-IP Dynamic Update Client](https://www.noip.com/download?page=win)
    - Refer to [Dynamic DNS (DDNS)](./ddns) if you are new to this.
8. Make sure the server has **Ethernet** connection.
:::caution Notes
**STRICTLY NO WIFI IS ALLOWED**
:::
9. Download and install Firebird Server. [Firebird Downloads](https://www.firebirdsql.org/en/firebird-5-0)
10. Make sure there is no antivirus other than Windows Defender. [Explanation](./server.md#operating-system)
11. Fill in the checklist and send it to us. [Checklist](https://docs.google.com/spreadsheets/d/1iqCgQMDHGcTYtt0HSgAsEAPTED1eltnQj8ywJdwYYx0/edit?usp=sharing)
