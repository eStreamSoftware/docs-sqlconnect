---
sidebar_position: 4
---

# SQL Connect Detector

SQL Connect Detector is an application for verifying/troubleshooting private cloud.

- If you want to check if your server is **eligible** for setup, you may click on **Pre-Installation Check**.
- If you have a ready private cloud server, and **have issue** connecting to your server, you may click on **Troubleshooting** to run analysis on your system.

## Download

[SQL Connect Detector v2.0.7 (SQL Drive)](https://drive.sql.com.my/s/ApwMiKBxP3x34f7)

![sql-connect-detector-1](../../../static/img/private-cloud/sql-connect-detector-1.png)

## Pre-Installation Check

- You may enter your **dynamic DNS (DDNS)** / **fix Public IP Address** here.

![sql-connect-detector-2](../../../static/img/private-cloud/sql-connect-detector-2.png)

- In the next windows, a report will show you if your server is eligible for the setup.
- Your server is ready to setup if **the report has every fields in <text style={{color: "#43a047"}}>green</text>**.
- Suggestions will be given based on the report result.

![sql-connect-detector-3](../../../static/img/private-cloud/sql-connect-detector-3.png)

## Troubleshooting

- You may enter your **dynamic DNS (DDNS)** / **fix Public IP Address** here.
- You may also change the port forwarded if you are not using the default.

![sql-connect-detector-4](../../../static/img/private-cloud/sql-connect-detector-4.png)

- In the next windows, a report will show you what issue your server is facing.
- Your server's state is healthy if **the report has no field marked in <text style={{color:"#f44336"}}>red</text>**.
- Suggestions / solutions will be given based on the report.

![sql-connect-detector-5](../../../static/img/private-cloud/sql-connect-detector-5.png)

## Issue: Virus/Unwanted Software

- Sometimes Windows Defender may flag detector as virus/unwanted software.

![sql-connect-detector-issue-1](../../../static/img/private-cloud/sql-connect-detector-issue-1.png)

- To resolve this, first, go to `Windows Settings > Update & Security > Windows Security > Virus & Threat Protection`.
- The interface would show a threat found and is similar to the one below.

![sql-connect-detector-issue-2](../../../static/img/private-cloud/sql-connect-detector-issue-2.png)

- Click on the threat, and allow it on device. After this you should be able to open SQL Connect Detector.

![sql-connect-detector-issue-3](../../../static/img/private-cloud/sql-connect-detector-issue-3.png)
