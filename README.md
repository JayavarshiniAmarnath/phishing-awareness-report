phishing-awareness-report
This project focuses on the detailed inspection and analysis of a phishing email sample to uncover common social engineering tactics used by attackers. The goal is to identify the warning signs of a phishing attempt, dissect the structure of the malicious email, and educate users on how to recognize and avoid falling victim to such threats.

📌 Objective
To analyze a suspected phishing email and identify common phishing traits such as:
- Spoofed sender address
- Mismatched or malicious URLs
- Urgent language to pressure users
- Suspicious attachments or links
- Spelling and grammar errors
- Inconsistencies in headers and formatting

🧠 What I Did
- Collected a real-world phishing email sample
- Inspected the email’s *sender address* and *headers*
- Hovered over embedded links to detect *mismatched URLs*
- Looked for signs of urgency, fear, or reward-based manipulation
- Checked for poor spelling, generic greetings, and lack of personalization
- Verified the presence of fake or malicious attachments

 🛠 Tools Used
- 📬 Gmail (for viewing sample spam email)
- 🛠 [MxToolbox – Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- 🕵 Manual URL inspection (hover method and right-click copy)
- 🛡 [VirusTotal](https://www.virustotal.com/) (for safe URL analysis)

📋 Key Findings                                                                                     
 ✅ Spoofed Sender - Appears to come from "PaypaI" (with a capital "I" instead of lowercase "l") 
 ⚠ Mismatched URL  - Link text says paypal.com but real link goes to http://phishingsite.ru 
 ⚠ Urgent Language -"Your account will be locked in 24 hours"                                   
 ❌ Grammar Errors - Multiple misspelled words like “plase” and “verfiy”                         
 ❓ Generic Greeting -Uses "Dear user" instead of recipient's name                                

