# Linux Cybersecurity & Privacy Hardening Project

## 🛡️ Στόχος
Δημιουργία ενός ασφαλούς και ανώνυμου περιβάλλοντος Linux σε παλιό προσωπικό υπολογιστή με χρήση εργαλείων για προστασία προσωπικών δεδομένων, κρυπτογράφηση, ανωνυμία και ενίσχυση ασφάλειας συστήματος.

---

## 🖥️ Περιβάλλον

- **OS**: Linux Mint
- **Hardware**: Παλαιό laptop (non-UEFI BIOS)-Είναι Legacy Mode
- **Network**: Ethernet & Wi-Fi

---

## 🔧 Βασικές Ρυθμίσεις & Hardening

### 🔒 Privacy & Security Εργαλεία:

- ✅ Tor (με Bridges)-safest option "ON"
- ✅ VPN χωρίς logs
- ✅ DuckDuckGo ως default search
- ✅ DNS encryption με `dnscrypt-proxy`
- ✅ MAC address spoofing (`macchanger`)
- ✅ Firewall (UFW: Deny incoming)
- ✅ Randomize MAC at boot
- ✅ `systemctl` configuration
- ✅ Post-install disk encryption
- ✅ GRUB password protection (hash)
- ✅ GRUB config backup με ασφαλή δικαιώματα πρόσβασης
- ✅ Sandboxed χρήση Tor browser & VM

---

## 🧪 Έλεγχος Ανωνυμίας

- Έλεγχος μέσω [browserleaks.com](https://browserleaks.com/)
- Δεν εντοπίστηκαν στοιχεία ταυτοποίησης ή IP leaks

---

## 📁 Χρήσιμα Αρχεία (στο repo)

- [grub_config.txt.txt](https://github.com/user-attachments/files/21631876/Text.Document.2.txt)
- [ufw_rules.txt](https://github.com/user-attachments/files/21631465/Text.Document.txt)
- [dnscrypt_proxy_config.conf.txt](https://github.com/user-attachments/files/21632846/Text.Document.3.txt)


---

## 🧠 Τι Έμαθα

- Πρακτική εφαρμογή εργαλείων ανωνυμίας και ασφάλειας
- Εξοικείωση με systemd και GRUB bootloader
- Linux disk encryption & network configuration
- Ανίχνευση διαρροών προσωπικών δεδομένων μέσω testing

---

## 🛠️ Tools

| Εργαλείο          | Χρήση                                 |
|------------------|----------------------------------------|
| Tor (with bridges)| Ανωνυμία & bypass censorship         |
| dnscrypt-proxy    | Κρυπτογράφηση DNS queries            |
| ufw               | Απλό firewall configuration          |
| macchanger        | MAC address spoofing                 |
| systemctl         | Service configuration                |
| GRUB              | Bootloader hardening                 |

---

## 👤 About me

📍 Είμαι Τεχνικός Υπολογιστικών Συστημάτων και ασχολούμαι με Cybersecurity, Linux & IT Support.  
📫 [LinkedIn Profile](https://www.linkedin.com/in/%CE%B5%CE%BC%CE%BC%CE%B1%CE%BD%CE%BF%CF%85%CE%B7%CE%BB-%CE%BA%CE%B1%CE%BD%CE%B1%CE%BA%CE%B7%CF%82-695809356/)
🌐 [kanakismanolis04@gmail.com](mailto:kanakismanolis04@gmail.com)
