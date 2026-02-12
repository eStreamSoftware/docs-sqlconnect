---
sidebar_position: 1
---

# Common Errors

Some solutions to common errors in SQL Connect.

## Black / Blank Screen

- Perform session reset following the steps: [Reset Session](../general/basic#logout-reset)

---

## Certificate Issues

### Windows 7

1. Download the certificate from [ISRG-ROOT-X1](https://x1.i.lencr.org).
2. Run the certificate file, you will see a windows as below.

    ![windows-7-certificate-issue-1](../../static/img/troubleshooting/windows-7-certificate-issue-1.png)

3. Install the certificate. Select the second option, click `Browse`.

    ![windows-7-certificate-issue-2](../../static/img/troubleshooting/windows-7-certificate-issue-2.png)

4. Select `Trusted Root Certificate Authorities`.

    ![windows-7-certificate-issue-3](../../static/img/troubleshooting/windows-7-certificate-issue-3.png)

5. Reboot PC.

### Windows 10

1. Update to latest Windows 10.
   ![windows-10-certificate-issue-1](../../static/img/troubleshooting/windows-10-certificate-issue-1.png)

2. Download the certificate from [ISRG-ROOT-X1](https://x1.i.lencr.org).
3. Run the certificate file, you will see a windows as below
    ![windows-10-certificate-issue-2](../../static/img/troubleshooting/windows-10-certificate-issue-2.png)

4. Install the certificate on Local Machine.
    ![windows-10-certificate-issue-3](../../static/img/troubleshooting/windows-10-certificate-issue-3.png)

5. Select the second option, click `Browse`.
   ![windows-10-certificate-issue-4](../../static/img/troubleshooting/windows-10-certificate-issue-4.png)

6. Select `Trusted Root Certificate Authorities`.
    ![windows-10-certificate-issue-5](../../static/img/troubleshooting/windows-10-certificate-issue-5.png)

7. Reboot PC.

---

## Empty Homepage

![not-registered](../../static/img/troubleshooting/not-registered.png)

- If you see the above screen, it indicates that your account is not activated yet. Kindly contact your dealer or our support team for further checking.

---

## Sign in error

![google-error-1](../../static/img/troubleshooting/google-error-1.png)
![google-error-2](../../static/img/troubleshooting/google-error-2.png)

- if you see errors like above, you will have to check your email's **date of birth**. Google classifies email which has an age less than **18 years old as child**. With a child email, you are **forbidden** from entering many websites available in the web including our SQL Connect services.
- Besides, make sure no **Family Link** email is used.

---

## There is no default printer selected

- Do a reset on the user session: [Reset Session](../general/basic#logout-reset)
