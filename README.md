# 🚨 **Google Dorking Guide for Cybersecurity Enthusiasts**

If you’re into **cybersecurity, OSINT, or ethical hacking**, mastering Google Dorking is a game changer. It helps you uncover hidden data, exposed files, and misconfigured systems — all using advanced search operators.

---

## 🔍 What is Google Dorking?

Google Dorking (also called Google Hacking) uses **advanced search queries** to find sensitive or specific information that is not easily visible through normal searches.

---

## 🧠 Basic Operators You Must Know

* `site:` → Search within a specific website
  `site:example.com`

* `filetype:` → Find specific file types
  `filetype:pdf confidential`

* `intitle:` → Search in page titles
  `intitle:"index of"`

* `inurl:` → Search in URLs
  `inurl:admin`

* `intext:` → Search within page content
  `intext:"password"`

---

## ⚡ Powerful Dork Examples

* Find open directories:
  `intitle:"index of" /backup`

* Exposed login pages:
  `inurl:login site:.com`

* Publicly accessible documents:
  `filetype:xlsx OR filetype:csv "email"`

* Configuration files:
  `filetype:env DB_PASSWORD`

* Cameras / IoT devices:
  `inurl:"viewerframe?mode="`

---

## 🔐 Use Cases

✔️ OSINT investigations
✔️ Bug bounty hunting
✔️ Finding exposed sensitive data
✔️ Reconnaissance in penetration testing

---

## ⚠️ Important Note

Use these techniques **ethically and legally**. Unauthorized access or misuse can lead to serious consequences. Always follow responsible disclosure.

---

## 🚀 Pro Tip

Combine operators for better results:

```
site:example.com filetype:pdf "internal use only"
```

---

💬 If you’re serious about cybersecurity, start practicing these queries and build your own dork list.

#CyberSecurity #EthicalHacking #OSINT #BugBounty #InfoSec #GoogleDorking
