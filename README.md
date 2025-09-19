### 🎯 Objective
Crack password hashes using dictionary and brute-force attacks with tools like **Hashcat**.

### 🛠️ Tools Required
- Hashcat  
- John the Ripper  
- Kali Linux  
- rockyou.txt wordlist  

### 📂 Deliverables
- Hash list  
- Cracked output

### 🚀 Example Commands

**1. Cracking with Dictionary Attack**
hashcat -m 0 -a 0 passwords rockyou.txt
