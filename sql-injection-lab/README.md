# 🔍 SQL Injection Lab (UNION-Based Attack)

## 🚨 Vulnerability Type
SQL Injection (UNION-Based)

---

## 📌 Objective
To exploit a vulnerable web application by injecting malicious SQL queries through a URL parameter and extracting data from the backend database.

---

## ⚙️ Tools Used
- Kali Linux  
- Firefox Browser  
- Local Vulnerable Lab Environment  

---

## 🧪 Methodology

### 1. Identify Injection Point
The application uses a URL parameter:

?id=1

---

### 2. Test for Vulnerability
The input parameter was manipulated to check for SQL injection behavior.

---

### 3. Exploit Using UNION Injection
A malicious payload was crafted and injected into the URL:

?id=1' UNION SELECT * FROM Songs WHERE '1'='1

---

### 4. Execute Payload
The payload was entered directly into the browser URL.

---

### 5. Result
The application returned all records from the Songs table, confirming successful SQL injection.

---

## 📊 Results

- Successfully exploited SQL injection vulnerability  
- Retrieved full dataset from backend database  
- Bypassed intended query restrictions  

---

## 🛡️ Security Insight

The vulnerability exists due to:
- Lack of input validation  
- Direct use of user input in SQL queries  
- Absence of prepared statements  

---

## 📸 Evidence
