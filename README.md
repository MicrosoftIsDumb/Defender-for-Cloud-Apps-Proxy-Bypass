# Defender-for-Cloud-Apps-Proxy-Bypass
Simple CLIENT side bypass for the Microsoft Defender for Cloud Apps Proxy

## Description
By setting a user agent string in your browser, you can bypass the protections offered by the Microsoft Defender for Cloud Apps Proxy. (Copy, Paste, Download, etc.)

### How To
1. Open your web browser (in this case we will be using Chrome)

2. Download an install the extension 'User-Agent Switcher for Chrome' from the Chrome Web Store

3. Go to the extension options

4. Create a user agent string named MS using any of the user agent strings in the 'User Agent Strings' section.

5. Set the new user agent as active within the extension

6. Navigate to outlook.office.com or any other service that's supposed to be protected by Microsoft Defender for Cloud Apps. The extension should show the text 'MS' if the user agent string is active.

7. Observe that you are now accessing the regular site and are not going through the Microsoft Defender for Cloud Apps Proxy.

### User Agent Strings
Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Teams/1.4.00.35564 Chrome/85.0.4183.121 Electron/10.4.7 Safari/537.36
Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) MicrosoftTeams-Preview/1.3.00.5153 Chrome/69.0.3497.128 Electron/4.2.12 Safari/537.36
Microsoft Office/16.0 (Microsoft Outlook 16.0.11425; Pro)
Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/605.1.15 (KHTML, like Gecko)
Mozilla/5.0 (iPhone; CPU iPhone OS 15_2_1 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Mobile/15E148
