# Task 7: Identify and Remove Suspicious Browser Extensions

## 🛡 Objective:
To understand the security risks of browser extensions and learn how to manage or remove potentially dangerous or over-permissive add-ons.

---

## 🔧 Tool Used:
- Mozilla Firefox (about:addons)

---

## 🕵️ Extension Reviewed:
### JSONView
- Purpose: Helps to view JSON documents in a readable format inside the browser.
- Permissions Observed: 
  - "Access your data for all websites" — this permission can be dangerous if misused by a malicious extension.

---

## ❌ Reason for Removal:
Even though JSONView is a useful tool, it requests access to all website data, which poses a risk if the extension ever gets compromised or replaced with malicious code in an update. Practicing good cyber hygiene means minimizing such over-permissive extensions unless strictly needed.

---

## 📸 Screenshots Included:
1. All installed extensions visible in Firefox.
2. Permissions page for JSONView showing optional permission: "Access your data for all websites."

---

## ✅ Steps Taken:
1. Opened Firefox's extension manager at `about:addons`.
2. Reviewed all installed extensions.
3. Inspected permissions of JSONView.
4. Identified potential risk.
5. Removed JSONView for better security.
6. Restarted Firefox.

---

## 🔍 Key Takeaways:
- Extensions with “Access all your data” should be reviewed carefully.
- Not all useful tools are safe if their permissions are too broad.
- Regular cleanup of browser extensions helps improve privacy and performance.

---

## 📚 Security Awareness:
Browser extensions can:
- Steal login sessions
- Record keystrokes
- Modify website content
- Insert malicious scripts

Always review permissions before installing and uninstall anything you don’t absolutely need.

---

## 🚀 GitHub Repo Contents:
- Screenshots (`Task 7.png`, `Task 7 two.png`)
- This `README.md`

