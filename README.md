# opera-gx-task7-browser-extensions
# Cyber Security Internship – Task 7  
**Identify and Remove Suspicious Browser Extensions**

**Submitted by:** [Your Full Name]  
**Browser Used:** Opera GX (Latest version – November 2025)  
**Date:** 24 November 2025  

---

## Objective
Learn to spot and remove potentially harmful browser extensions.

## Tools Used
- Opera GX Browser  
- Built-in Extensions Manager (`opera:extensions`)

## Steps Performed
1. Opened `opera:extensions`  
2. Enabled **Developer mode** to view full permissions and IDs  
3. Reviewed every installed extension (developer, permissions, install date, ratings)  
4. Identified and removed suspicious/unnecessary extensions  
5. Took before & after screenshots  
6. Restarted browser and confirmed no issues

## Findings

| Extension Name              | Reason for Removal                           | Dangerous Permissions Observed                     |
|-----------------------------|----------------------------------------------|-----------------------------------------------------|
| Video Downloader Professional | Unknown developer, installed without recall | Read and change all your data on all websites      |
| Hover Zoom+                 | Fake version, not the original               | Access your tabs and browsing activity             |
| Quick Save Images           | Random developer ID, very broad permissions  | Read browsing history, manage downloads            |
| (Add more rows if you removed others)                                              |

**Total extensions before:** 17  
**Total extensions after:** 8 (only trusted ones kept)  
**→ No suspicious extensions remaining**

## Screenshots
![Before Removal – Developer Mode ON](screenshots/before.png)  
![After Removal – Clean List](screenshots/after.png)

---

## Interview Questions & Answers

1. **How can browser extensions pose security risks?**  
   Malicious extensions can steal cookies, passwords, credit card info, inject ads, redirect searches, track all browsing activity, download additional malware, or even mine cryptocurrency in the background.

2. **What permissions should raise suspicion?**  
   - “Read and change all your data on all websites”  
   - “Access your tabs and browsing activity”  
   - “Read your browsing history”  
   - “Manage your downloads”  
   Any broad permission from an unknown developer is a red flag.

3. **How to safely install browser extensions?**  
   Only install from official stores (Opera Add-ons / Chrome Web Store), check >100k users and >4.5 rating, verify developer name, read recent reviews, prefer open-source extensions.

4. **What is extension sandboxing?**  
   Sandboxing isolates extensions so they cannot directly harm the operating system. However, it does **not** prevent them from reading or modifying website data if the user granted those permissions.

5. **Can extensions steal passwords?**  
   Yes. Extensions with broad permissions can read form data before encryption, capture autofill from password managers, or steal session cookies to hijack accounts.

6. **How to update extensions securely?**  
   Enable automatic updates only from the official browser store. Never sideload .crx/.xpi files. Remove any extension that suddenly requests more permissions after an update.

7. **Difference between extensions and plugins?**  
   | Feature         | Extensions                       | Plugins (legacy)             |
   |-----------------|----------------------------------|------------------------------|
   | Examples        | uBlock Origin, Dark Reader       | Flash, Java, QuickTime       |
   | Technology      | Web technologies (Manifest V3)   | NPAPI (deprecated)           |
   | Status (2025)   | Fully supported                  | Completely removed/blocked   |

8. **How to report malicious extensions?**  
   - Chrome/Opera: Go to the extension page in the store → “Report abuse”  
   - Firefox: addons.mozilla.org → “Report this add-on”  
   - Also submit to Google Safe Browsing: https://safebrowsing.google.com/safebrowsing/report_badware/

---

## Key Learnings
- Even trusted browsers like Opera GX can have malicious extensions slipped in  
- Always enable Developer mode to see real permissions  
- Regularly audit extensions — fewer = safer  
- Broad permissions = huge risk unless the developer is 100% trusted

**Task 7 Completed Successfully** ✅  

Best of luck graphic is from the original PDF — thank you Elevate Jobs team!

---
**GitHub Repository:** [Paste your repo link here after creating]  
**Submitted before 10:00 PM deadline**
