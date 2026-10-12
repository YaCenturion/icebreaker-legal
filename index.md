# Privacy Policy — Icebreaker: Route Ahead

**Last updated: 12 October 2026**

Icebreaker: Route Ahead (the "App", package `com.frostpaw.icebreaker`) is a VPN client for a closed
group of users. It is distributed by invitation and contains no public servers. This policy explains
what the App does and does not do with data.

## 1. No accounts, no personal data

The App does not ask for a name, e-mail address, phone number or any other personal detail, and it
has no registration or sign-up.

Access is granted by the operator of the servers, who gives each participant a personal access code.
The code is entered once, used to decrypt that participant's server list, and is **not stored** on
the device. Without a code the App has nothing to connect to.

## 2. What is stored on the device

The following is kept locally, on the device only, and is never transmitted to the developer:

- the list of servers obtained from the subscription;
- the App's settings (routing rules, the selected server, interface preferences);
- the identifier of the participant whose access code was entered.

Uninstalling the App removes all of it. There is no cloud backup of this data on our side.

## 3. No analytics, no advertising, no tracking

The App contains no advertising SDKs, no analytics, no crash-reporting services and no tracking
identifiers. It makes no network requests to the developer.

## 4. Traffic through the VPN

While a connection is active, the device's network traffic is routed through servers operated by the
person who issued the access code. Those servers are private infrastructure, not a commercial
service, and they are not operated for the purpose of inspecting traffic. No browsing history,
connection logs or traffic contents are collected, stored or sold by the developer.

Subscription updates are fetched over HTTPS from the address contained in the participant's code.

## 5. Permissions

- **VPN (VpnService)** — the core function: establishing the tunnel.
- **Internet / network state** — connecting to servers and detecting network changes.
- **Notifications** — the ongoing notification Android requires while a VPN is active.
- **Camera** — optional, only if the user chooses to add a server by scanning a QR code. No image is
  stored or transmitted.

## 6. Children

The App is not directed at children and collects no data from anyone, including children under 13.

## 7. Open source

The App is based on the open-source project v2rayNG, licensed under GPL-3.0.

## 8. Changes

Any change to this policy is published on this page with a new revision date.

## 9. Contact

Questions about this policy: boris.drozdovski@gmail.com
