# AdGuard Anti-Porn DNS Service

I have created this repository and corresponding service so that friends and family can use this information to help prevent access to adult content on the internet. No solution is perfect, but perhaps this will be of some help to protect children as well as adults from unwelcome content.

This is primarily targeted at mobile devices that are either Android or iOS. It will supercede **all** DNS requests to prevent access to many adult websites while the phone/tablet is on wifi ***as well as cellular*** networks. These settings *may* not work if the device has other VPN options enabled.

Logging is diabled for DNS queries, but anonymized metrics are collected. I cannot associate DNS queries with users. This service is provided "as-is" with no gurantees or warranties of any kind. If you experience issues, you can easily undo the settings. 

## Setup

There are two options to choose from:

- Block adult content only
- Block adult content and advertisements

> Please note that blocking advertisements may have an adverse effect on your browsing experience. Some websites will refuse you entry because you are using an ad blocker. Other sites may fail to work properly when an ad blocker is enabled.

### Andoid setup

1. Navigate to **Settings** -> **Network & internet** -> **Private DNS**
2. Select **Private DNS provider hostname** and enter one of the following:
    - For blocking adult content only: "adguardp.cloud.hellzbellz.net"
    - For blocking adult content and ads: "adguard.cloud.hellzbellz.net"
3. Click **Save**


### iOS setup

1. Using Safari on your iOS device, visit one of the following links to download the config file:
    - For blocking adult content only: [link](https://raw.githubusercontent.com/marlobello/adguardp/main/adguardp.mobileconfig)
    - For blocking adult content and ads: [link](https://raw.githubusercontent.com/marlobello/adguardp/main/adguard.mobileconfig)
2. Safari should ask you if you want to download a configuration profile, click **Allow**
3. Upon successful download, click **Close**
3. Open the **Settings** app
4. Navigate to **VPN & Device Management** -> **Downloaded Profile**
5. Click **Install** and input your PIN
6. Click **Install** (again)
7. Click **Install** (button at the bottom of the screen)
8. Click **Done**

## Removal

If your web browsing is not behaving as you expect or is not working at all, and you know that your internet connection is working--you may want to remove this setting.

### Android removal

1. Navigate to **Settings** -> **Network & internet** -> **Private DNS**
2. Select **Automatic**
3. Click **Save**

### iOS removal

1. Open the **Settings** app
2. Navigate to **VPN & Device Management** -> **Configuration Profile** -> **Encrypted DNS**
3. Click **Remove Profile** and input your PIN
4. Click **Remove** to confirm