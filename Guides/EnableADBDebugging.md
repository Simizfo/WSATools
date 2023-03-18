# ⚒️ Enable and Troubleshoot ADB Debugging

If you're installing the Windows Subsystem for Android for the first time, you will need to enable the ADB Debugging feature.

If you're encountering issues while using WSATools, this is something that you need to check. Sometimes ADB Debugging gets stuck and needs to be resetted.

## 1. Enable ADB Debugging

- Open whe Windows Subsystem for Android Settings app.

<img width="265" alt="image" src="https://user-images.githubusercontent.com/29689637/226114395-81f2c032-69c4-4494-84f0-77111beb9a82.png">

- Go to the Developer tab

<img width="243" alt="image" src="https://user-images.githubusercontent.com/29689637/226114407-ae9c9213-8dd4-4fb0-b546-eb1895b7d2ce.png">

- Turn Developer Mode on

<img width="639" alt="image" src="https://user-images.githubusercontent.com/29689637/226114421-d4315b48-0490-41fe-ae95-5529413a9343.png">

- Try installing your app with WSATools. You'll get a popup asking for authorization. Check "Always allow from this Computer" and click on Allow.

<img width="336" alt="image" src="https://user-images.githubusercontent.com/29689637/226115178-b32acd85-83e9-481c-baad-dfbadd47962c.png">

Done! If this was already enabled, then proceed trying with the next step.

## 2. Reset ADB authorizations

- Click on the "Manage developer settings" text

<img width="639" alt="image" src="https://user-images.githubusercontent.com/29689637/226114421-d4315b48-0490-41fe-ae95-5529413a9343.png">

- A new window should open. 
- Scroll until you see "Revoke USB debugging authorizations", click on it and confirm.

<img width="321" alt="image" src="https://user-images.githubusercontent.com/29689637/226114563-010eb469-b868-473a-975a-e18780ee3c5a.png">

- Try installing your app with WSATools. You'll get a popup asking for authorization. Check "Always allow from this Computer" and click on Allow.

<img width="336" alt="image" src="https://user-images.githubusercontent.com/29689637/226115178-b32acd85-83e9-481c-baad-dfbadd47962c.png">
