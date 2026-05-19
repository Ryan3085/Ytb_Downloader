# YouTube .any downloader
**Tampermonkey Script to Download YouTube Videos in One Click**

## How it works (The Automation)
A normal process to download a YouTube video involves copying the URL, opening a third-party converter like noTube, dodging intrusive popups, clicking multiple buttons, and waiting for countdowns. 

**This script automates the entire process for you.**

## Script Features
When you watch a video on YouTube, this script optimizes your downloading experience by acting on both platforms:

1.  **The YouTube Tab (Native Integration):**
    A discreet, native-looking **"Download" button** is injected seamlessly into the YouTube interface, right next to the "Like" (thumbs up) button. It blends perfectly with YouTube's dark mode.

2.  **The noTube Tab (Full Automation & Bypass):**
    When you click the download button, a new tab opens to `notube.lol` and the script takes full control:
    * **Zero-Click Conversion:** It automatically pastes your YouTube URL into the search bar and submits the form instantly.
    * **Bypass the 30-Second Limit:** The script instantly nukes noTube's cookies, `localStorage`, and `sessionStorage` upon loading. This **should be** completely bypasses their annoying 30-second wait timer between consecutive downloads.
    * **Ad-Free & Auto-Close:** It intercepts the raw download link, skipping fake buttons and pop-up ads. Once the file starts downloading to your computer, the script **automatically closes the tab**, returning you seamlessly to your YouTube video.

**Requirement:** Active permission to execute user scripts : https://www.tampermonkey.net/faq.php?q=Q209#Q209
