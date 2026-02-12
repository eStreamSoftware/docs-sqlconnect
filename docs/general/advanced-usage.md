---
sidebar_position: 3
---

# Advanced Usage

## Copy Image into Rich Text Editor

1. Firstly, [_upload_](./basic#upload) the image file to SQL Connect
2. In SQL Account / SQL Payroll, go to `View` > `File Explorer`
3. Navigate to `This PC` > `SQL Drive on SQL Connect` > double click to open your image file
4. Select All (or press `Ctrl + A`), and then copy it.
5. Go to the rich text editor, paste the image you just copy.

![copy-image-rich-1](../../static/img/general/copy-image-rich-1.png)
![copy-image-rich-2](../../static/img/general/copy-image-rich-2.png)
![copy-image-rich-3](../../static/img/general/copy-image-rich-3.png)
![copy-image-rich-4](../../static/img/general/copy-image-rich-4.png)

---

## Delete Files in SQL Drive

1. In SQL Account / SQL Payroll, navigate to `View` > `File Explorer`

    ![delete-files-1](../../static/img/general/delete-files-1.png)

2. Go to `SQL Drive on SQL Connect`, right click on the file and select `Delete`

    ![delete-files-2](../../static/img/general/delete-files-2.png)

---

## Kill Firebird Connections From Application

> This action requires ADMIN user privilege

### Login Screen

:::warning
    The last logged-in user must be ADMIN; otherwise, the process will fail.
:::

1. In the login screen, click on the `Settings ⚙️`

    ![kill-firebird-connections-1-1](../../static/img/general/kill-firebird-connections-1-1.png)

2. Right click on the database, select `Show Active Connections...`

    ![kill-firebird-connections-1-2](../../static/img/general/kill-firebird-connections-1-2.png)

3. Press on the "**Kill**" button to close the connection

    ![kill-firebird-connections-1-3](../../static/img/general/kill-firebird-connections-1-3.png)

### After Login

1. In the application, navigate to `File` > `Show Active Connections...`

    ![kill-firebird-connections-2-1](../../static/img/general/kill-firebird-connections-2-1.png)

2. Press on the "**Kill**" button to close the connection

    ![kill-firebird-connections-1-3](../../static/img/general/kill-firebird-connections-1-3.png)

---

## Link with SQL Pos

:::info
This guide applies only to the public cloud; for private‑cloud deployments, you can link as usual, similar to a local setup.
:::

1. First, request SQL Pos integration from your support/dealers. You will receive a file link. In the file, you can find all the information required to link local SQL Pos with SQL Account. Example on how the file looks like:

    ![link-with-sql-pos-1](../../static/img/general/link-with-sql-pos-1.png)

2. In SQL Pos, fill in accordingly.

    ![link-with-sql-pos-2](../../static/img/general/link-with-sql-pos-2.png)

---

## Printing Half Page

### Windows 10

1. Navigate to `Control Panel` > `View devices and printers`
2. Next, select the printer and click on `Print server properties`, add a new page size (half page)

    ![half-page-1](../../static/img/general/half-page-1.png)

3. Close the form dialog, then click `Add a device` at the top left of the control panel. Add a duplicate printer profile for the desired printer.

    ![half-page-2](../../static/img/general/half-page-2.png)

4. Right click on the printer, and go to `printer preferences`, click on the profile we had created.

    ![half-page-3](../../static/img/general/half-page-3.png)

5. Go to "Advanced", configure the printer profile to use the paper size we created before.

    ![half-page-4](../../static/img/general/half-page-4.png)

6. Next, right click on the printer again, go to `printer properties`.

    ![half-page-5](../../static/img/general/half-page-5.png)

7. Set the default paper size to the custom paper size we created.

    ![half-page-6](../../static/img/general/half-page-6.png)

8. Once you have done with the above settings, login into your SQL Connect session and test print with the following steps:

    ![half-page-7](../../static/img/general/half-page-7.png)
    ![half-page-8](../../static/img/general/half-page-8.png)

### Windows 11

1. Search "Printers" in Windows search bar

    ![half-page-win11-1](../../static/img/general/half-page-win11-1.png)

2. Select on `Print server properties`, add a new page size (half page)

    ![half-page-win11-2](../../static/img/general/half-page-win11-2.png)

3. click `Add a device` to add a duplicate printer profile for the desired printer

    ![half-page-win11-3](../../static/img/general/half-page-win11-3.png)

4. Click on the desired printer, go to `printer preferences`, select the profile create in previous step

    ![half-page-win11-4](../../static/img/general/half-page-win11-4.png)

5. Go to "Advanced", configure the printer profile to use the paper size we created before.
6. Next, go to `printer properties`.
7. Set the default paper size to the custom paper size we created.
8. That's all. 🥳

---

## Saving PDF

If you want to download PDF file, save it to the "**Download**" folder in the "**SQL Drive on SQL Connect**"

![save-pdf-1](../../static/img/general/save-pdf-1.png)

The PDF file will be opened in a new tab, click download and save the file to local PC.

![save-pdf-2](../../static/img/general/save-pdf-2.png)

---

## Signout (Private Cloud only)

:::info
**The is exclusive for private cloud users only.** In private cloud, the user has control over the server. Thus, the administrator has the right to signout connections.
:::

![signout-conn](../../static/img/general/signout-conn.png)

---

## SQL Connect Printing

In SQL Connect, we have two groups of users (Public cloud users & private cloud users). As a private cloud users, you gain an extra option which able to print directly to your local printer as long as the printer is accessible from your server. While for public, you can select any option listed below:

- [PDF Print](#pdf-print)
- [SQL Connect Printer](#sql-connect-printer)
- [SQL Drive method](#sql-drive-method)

### PDF Print

:::info
This feature is available in specific versions:

- SQL Account version 5.2024.976.842 and above
- SQL Payroll version 1.2024.254.204 and above

:::
In SQL Account, go to the report preview, click on the PDF button located at the top left.

![pdf-print-1](../../static/img/general/pdf-print-1.png)

The pdf will be open in your new tab, you can then select your local printer and print.

---

### SQL Connect Printer

![sql-connect-printer-1](../../static/img/general/sql-connect-printer-1.png)

By using "**SQL Connect Printer**", you will then able to access the browser print dialog which has the right to utilize your local printer. From there, you can select the printer you want, size you like and so on. After select all the options you wish, click print. Below is an example of chrome print dialog:

![sql-connect-printer-2](../../static/img/general/sql-connect-printer-2.png)

---

### SQL Drive method

This method should produce identical result compared with [PDF Print](#pdf-print). In SQL applications, export the report as PDF and save it to **"SQL Drive on SQL Connect" > Download** directory

![sql-drive-method-1](../../static/img/general/sql-drive-method-1.png)
![sql-drive-method-2](../../static/img/general/sql-drive-method-2.png)
![sql-drive-method-3](../../static/img/general/sql-drive-method-3.png)
![sql-drive-method-4](../../static/img/general/sql-drive-method-4.png)
![sql-drive-method-5](../../static/img/general/sql-drive-method-5.png)

---

## SQL Connect Subscription Checker

To check your subscription, you can open the app by following the steps below:

1. Go to `File > Run`
2. Select `SQL Connect Subscription Checker`

![sqlconnect-checksub-1](../../static/img/general/sqlconnect-checksub-1.png)

If the app is not there, you can add it manually by following the steps in [SQL Utilities](#sql-utilities)

---

## SQL Utilities

By default, SQL Connect has already generate the list when you connect to a session. But if it didn't show up, you can add them manually by following the steps below:

1. Go to `File > Run > Configure Program...`
2. Add the utilities software from here: `C:\eStream\Utilities`
3. After add successfully, the program should be available at `File > Run > ...`

- Summary:

![sql-utilities-1](../../static/img/general/sql-utilities-1.png)
![sql-utilities-2](../../static/img/general/sql-utilities-2.png)
![sql-utilities-3](../../static/img/general/sql-utilities-3.png)
![sql-utilities-4](../../static/img/general/sql-utilities-4.png)
