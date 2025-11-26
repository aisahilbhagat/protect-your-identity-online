🦆 The Duck-Temp Relay
Secure & Anonymous Verification on Public Devices
Privacy ShieldComplexityCost

The Problem: You are on a public computer (Library, School, Internet Cafe). You need to sign up for a website, but you don't want to log into your personal Gmail/Outlook on an insecure device, and the website blocks standard temp-mail domains.

The Solution: A "Relay" method using DuckDuckGo’s Email Protection to sanitize and forward emails to a temporary inbox.

🔄 How It Works
By wrapping a "low reputation" temporary email inside a "high reputation" Duck address, you bypass spam filters while keeping your personal inbox safe.

mermaid

graph LR
    A[Website Login] -->|Sends OTP| B(username@duck.com)
    B -->|Forwards & Strips Trackers| C{Temp-Mail Inbox}
    C -->|You Read Code Here| D[Public PC Browser]
🌟 Why Use This Method?
Feature	Benefit
🛡️ Zero Login Risk	Never type your real email password on a public keyboard (protection against keyloggers).
🚫 Bypass Blocks	Many sites block temp-mail.org but accept duck.com addresses.
🧹 Privacy First	DuckDuckGo strips invisible trackers from the verification email before it hits the temp inbox.
⚡ Instant	Takes less than 60 seconds to set up.
🛠️ Prerequisites
You only need two tabs open in your browser:

The Destination: A Temporary Email Provider (e.g., Temp-Mail, 10MinuteMail, or Guerrilla Mail).
The Bridge: DuckDuckGo Email Protection.
🚀 Step-by-Step Guide
Phase 1: Acquire the Target
Open your preferred Temp Mail site.
Copy the generated email address to your clipboard.
Example: johndoe@xxyyzz.com

Phase 2: Build the Bridge
Navigate to duckduckgo.com/email.
Click Get Started → Next → Next.
Create your Duck Address:
Choose a random throwaway name.
Example: library-user-99@duck.com
Set the Forwarding Address:
Paste the Temp Mail address you copied in Phase 1.
Click Continue.
Phase 3: Verify & Deploy
DuckDuckGo will send a verification code to the Temp Mail.
Switch tabs back to your Temp Mail inbox.
Copy the code (usually a bold 6-digit number) and paste it into the DuckDuckGo tab.
Success! You will see:
text

library-user-99@duck.com is yours!
Click Next or I'll do this later to finish.
Phase 4: Usage
Use your new Duck Address (library-user-99@duck.com) on any website requiring login. Watch the Temp Mail tab for your One-Time Passwords (OTPs) or confirmation links.

⚠️ Critical Warnings
Ephemeral Nature: Do NOT use this for accounts you need to keep forever (like Banking, Government, or Primary Social Media). Once you close the Temp Mail tab, you lose access to that inbox forever. You will never be able to reset your password.
Public Visibility: While rare, some temp mail inboxes are public. Do not receive sensitive personal data (SSN, private photos) through this method.
🔧 Troubleshooting
<details> <summary><strong>Click to expand Troubleshooting Tips</strong></summary>
"The website still says invalid email"
Some websites are extremely strict. Try using a Duck Address that sounds "real" (e.g., alex.smith.work@duck.com instead of sdfgsdfg@duck.com).

"I'm not receiving the OTP"
Refresh the Temp Mail page.
DuckDuckGo forwarding usually takes 2-5 seconds, but can take up to a minute.
Ensure you didn't close the DuckDuckGo tab before the "Success" screen appeared.
"DuckDuckGo says my forwarding address is invalid"
Some very obscure temp mail domains are blocked by DuckDuckGo. If this happens, simply switch to a different temp mail provider (e.g., switch from Temp-Mail.org to GuerrillaMail).

</details>
<div align="center">
Stay safe. Stay private. Leave no trace.

</div>
