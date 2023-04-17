# OS Hardening

This repository contains an extensive list of OS hardening practices for most popular platforms used worldwide.

Operating system (OS) hardening is the process of securing an operating system by reducing its attack surface, minimizing vulnerabilities, and limiting the ability of attackers to exploit the system. The goal of OS hardening is to improve the overall security of the system by removing unnecessary software and services, applying security updates and patches, and configuring the system settings to minimize security risks. By hardening the OS, organizations can reduce the risk of unauthorized access, data breaches, and other security incidents.

## Contents

- 1.0 Android
- 2.0 Windows (coming soon)
- 3.0 Linux (coming soon)
- 4.0 IOS (in the future)

## Getting Started

To use this study guide, simply clone the repository to your local machine or download the .docx or .pdf file. The guide is provided in PDF format, which can be viewed on any device with a PDF reader.

# 1.0 Android hardening

<p align="center">
  <img src="https://logos-world.net/wp-content/uploads/2021/08/Android-Logo-2019-present.jpg" width="70%">
</p>

## Introduction

Android is a mobile operating system based on the Linux kernel and developed by Google. It is designed primarily for touchscreen mobile devices such as smartphones and tablets. Android offers a rich set of features and capabilities, including a customizable home screen, support for multiple user accounts, access to the Google Play Store and a vast array of third-party apps, built-in support for popular Google services such as Gmail, Google Maps, and Google Assistant, and advanced security features such as app sandboxing and hardware-based encryption. Android is open-source software, which means that its source code is freely available for anyone to use and modify under the terms of the Apache License.

## Top up-to-day hardening practices

**1.	Uninstall or disable unnecessary software on your device.** 

- Every Android-based smartphone comes with default settings and software, much of which is simply bloatware and unnecessary for regular use. Each piece of software is a potential attack vector that can be exploited to gain access to your device. For instance, if application XYZ is manipulated or exploited, it may be used by malicious actors to gain access to your device.

**2.	Disable unnecessary features or keep them turned off until you need them.** 

- NFC, Bluetooth, and location services increase the attack surface of your device. Turn them off if you don't need them or enable them only when needed.

**3.	Keep your software updated.**

- The most crucial aspect of this point is the core of your device - its system. Generally, every new version of Android is better and more secure than the previous one, as developers update features and fix vulnerabilities. However, sometimes an update can fix one vulnerability and open another one in a different place. In general, keeping your device and all your applications up-to-date is the best way to secure your device.

- Enable auto update of software including system and your additional software.

**4.	Don't install unnecessary software.** 

- Every additional piece of software is another possible attack vector. The less the attack surface, the lower the possibility of an attack. Keep things simple and tidy.

**5.	Apply the "Least Privilege" rule.** 

- Each of your applications has a predefined set of permissions required to work correctly. You can decide which permissions should be granted or denied. Some applications require too many permissions for their tasks. It is your responsibility to define the necessary permissions. For example, does the calculator need access to your camera and microphone?

**6.	Secure your device with a lock screen.** 

- There are many locking options, including biometry, face recognition, pattern, pin, password, token, and more. Choose the ideal way to lock your device that will fit your needs. Remember, each of the methods mentioned above may be tampered with in one way or another. If it were up to me, I would choose biometry to unlock and a password for privileged access to the device.

**7.	Enable encryption.** 

- If your device has encryption capabilities, use them wisely and save the recovery key in case you forget your password; otherwise, you may lose your data forever.

**8.	Enable secure boot.**

- Many of the newer devices have a secure boot feature that provides an additional layer of protection. Secure boot is a system feature that protects the kernel and BIOS/UEFI from manipulation through signatures, certificates, and hardware solutions. In newer smartphones, secure boot is implemented by default, so enabling it is not necessary. Sometimes you have to turn it on your own, with developer settings enabled.

**9.	Enable lockout.** 

- Lockout is a security feature that protects the device from brute force or dictionary attacks on your password. After several unsuccessful attempts to unlock your device with the incorrect password, the device will be locked, requiring a special recovery key or another way to authenticate ownership.

**10.	Enable remote wipe.** 

- Remote wipe will protect your data in case of theft or loss. When the incident occurs, you will be able to delete all your data from your device permanently and make it impossible for malicious actors to recover it. All you have to do is sign in remotely to your device or software account and use the remote wipe option.

**11.	Enable "Find My Device."**

- When this feature is enabled, you will be able to track down your lost device via GPS signal and loud sound and vibration.

**12.	Install antivirus software.** 

- Antivirus software often provides a considerable amount of additional protection, including real-time protection, up-to-date signatures, scanning incoming data, anti-theft and track a device option, and more. Choose the one that fits your needs perfectly.

**13.	Install VPN software.**

- Installing VPN software is a must if you want to access restricted data or keep your privacy intact. VPN works like an external server, providing you an artificial IP, and encrypting your data to keep you less visible on the internet.

**14.	Disable the option "install from unknown sources."**

- Most smartphones have this option disabled, and it should remain that way. Installing software only from known and secure sources will keep your device safe. If you have this option enabled, disable it or use it very wisely.

**15.	Use app locking feature.**

- Consider using an app locking feature that requires a PIN or other authentication to access specific apps. Critical apps such as email accounts, bank accounts, and your private notes or gallery require an additional layer of security.

**16.	Disable USB debugging.**

- USB debugging can be used to bypass security controls and gain access to the device.

**17.	Use secure messaging app.**

- Consider using a secure messaging app that offers end-to-end encryption, such as Signal or WhatsApp, to help protect the privacy of messages.

**18.	Disable automatic Wi-Fi and Bluetooth connections.**

- This step will prevent the device from connecting to untrusted or unknown networks or devices.

**19.	Use privacy screen protector.**

- Consider using a privacy screen protector to prevent others from seeing your screen and protect your privacy from shoulder surfing.

**20.	Disable unnecessary cloud syncing and backup services.**

- This step will help you reduce the amount of personal data stored on third-party servers.

**21.	Use virtualization.**

- Consider using virtual machine or sandboxing software to run potentially risky applications in a separate and isolated environment.

**22.	Disable developer options, or make sure its disabled.**

**23.	Disable bootloader feauture, or make sure its disabled.**

**24.	Enable USB data block feature.**

- This will prevent external devices from connecting to your system, which can sucesfully isolate your device from data transmission. This option will make charging your device from public places safe.

**25.	Implement Data Loss Prevention (DLP) software solution.**

- DLP's main goal is to prevent your data from leaking or getting lost.

## Enterprise solutions

1.	Android Enterprise provides a suite of management solutions that includes features such as device encryption, secure boot, and network security protocols. It also includes a feature called "Work Profile," which enables users to keep their work and personal data separate on the same device.

2.	Samsung Knox is a security solution that offers features such as secure boot, device encryption, and biometric authentication. It also includes a feature called "Secure Folder," which enables users to keep their work and personal data separate on the same device.

3.	BlackBerry Enterprise Mobility Suite offers a range of security features, including secure boot, device encryption, and containerization of work apps and data. It also includes a feature called "BlackBerry Dynamics," which enables secure app development and management.

4.	Workspace ONE is a mobile device management solution that offers features such as secure boot, device encryption, and remote wipe capabilities. It also includes a feature called "Workspace ONE UEM," which enables the management of multiple devices and apps from a single console.

5.	MobileIron is a mobile device management solution that offers features such as secure boot, device encryption, and containerization of work apps and data. It also includes a feature called "MobileIron Threat Defense," which provides real-time protection against malware and other threats.

## Additional security practices

**1.	Avoid installing unknown software.**

-	Do not download software from unknown sources, such as unfamiliar domains. If you must download one, verify the URL and certificates to confirm the identity.

-	Be cautious when using app stores, such as Google Play Store, Samsung Apps, or others, as they may contain malicious software. Always confirm that you are downloading the official app, not a substitute.

-	Review app ratings and opinions before installing an app.

**2.	Always change default passwords in applications and systems.**

**3.	Use strong passwords and consider the following practices:**

-	Passwords should be at least 12 characters long. Longer passwords are generally more secure than shorter ones.

-	Passwords should be complex and include a mix of uppercase and lowercase letters, numbers, and symbols.

-	Passwords should not include easily guessable information, such as personal information or common words.

-	Passwords should be unique and not reused across multiple accounts.

-	Avoid using dictionary words, sequential numbers or letters, or simple variations of common phrases or words.

-	Using a password manager to generate and store complex passwords is also recommended.

**4.	Regularly review device settings to ensure that privacy and security settings are appropriately configured.**

- Each update or patch can implement new features, which can potentially introduce vulnerabilities that could put your device at risk. Stay up-to-date with system changes.

**5.	Always use a strong and unique password for your Google account** to help prevent unauthorized access to Google services and data.

**6.	Regularly review the security settings of the Google account** associated with the device to ensure that they are appropriately configured.

**7.	Be cautious when connecting to public Wi-Fi.**

- Avoid connecting to public Wi-Fi networks that are not secured with a password or that are known to be untrustworthy.

**8.	Avoid rooting or jailbreaking the device,** as it can weaken its security and allow malicious apps to gain root access.

**9.	Regularly back up important data to a secure location,** such as a cloud storage service, to ensure that it can be recovered in the event of data loss or device failure.

### Sources

`National Institute of Standards and Technology. (2020). Mobile Device Security. https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-124r1.pdf`

`MITRE. (2021). D3FEND: Mobile Device Management. https://d3fend.mitre.org/tactic/mobile-device-management/`

`Computing Technology Industry Association. (2020). Mobile Device Security for Android. https://www.comptia.org/content/guides/mobile-device-security-for-android`

`National Security Agency. (2019). Securing Mobility: Best Practices for Securing Mobile Devices. https://media.defense.gov/2020/Oct/05/2002501096/-1/-1/0/CSI_SECURING_MOBILITY_BEST_PRACTICES_2020.PDF`

`OWASP. (2019). Mobile Security Testing Guide. https://owasp.org/MSWG/Android_Platform_Architecture.html`

`MITRE. (2021). ATT&CK for Mobile. https://attack.mitre.org/mobile/`

`OPSEC. (2021). Mobile Device Security. https://www.opsecsecurity.com/resources/mobile-device-security`
___
## Contributing

If you notice any errors or have suggestions for improving the study guide, feel free to submit a pull request or open an issue. Your contributions are greatly appreciated. The study guide is still during the editing process, and will be updated after every major update. The project itself will change through time, as more and more features will be added to it.

## License

This study guide is licensed under the MIT License. You are free to use, modify, and distribute it for personal or commercial purposes.
