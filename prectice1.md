# RHCSA (EX200)

---

## NODE 1

### Question 1: Setup Networking
Configure the network with the following details:
- IP Address: `172.25.10.11`
- Subnet Mask: `255.255.255.0`
- Default Gateway: `172.25.10.254`
- Nameserver: `172.25.254.254`
- Hostname: `primary.netX.example.com`

---

### Question 2: Yum Repository Configuration
Configure yum repositories using the following URLs:
- http://content.example.com/rhel9/x86_64/dvd/BaseOS
- http://content.example.com/rhel9/x86_64/dvd/AppStream

---

### Question 3: Debug SELinux
The `httpd` service is running on non-standard port **82**, but the system is unable to access it.

**Requirements:**
- HTML files are stored in `/var/www/html`
- Do not modify the content
- Service must start at boot
- Output of:
  ```bash
  curl localhost:82/file1
should be:
```
Welcome to the EX200 Exam!
```
### Question 4: Configure Cron Job
- natasha runs /bin/echo hello daily at 13:30
- natasha runs /bin/echo new1 every 3 minutes

### Question 5: Users and Groups
- Create sysadmin group.
- Users: ryan, sarah (secondary group sysadmin), harry (no login shell).
  Password: atenorth

### Question 6: Collaborative Directory
Create /common/admin with sysadmin group ownership and SGID.

### Question 7: Configure NTP
Configure NTP client:
utility.domain0.example.com

### Question 8: Find Command
Copy files owned by simone to /root/found

### Question 9: Configure AutoFS
Automount remoteuser5 home from:
node1.domain5.example.com:/rhome/remoteuser5

### Question 10: User with Specific UID
User james, UID 2112, password sestiver

### Question 11: Sudo Privilege
Group elite passwordless sudo

### Question 12: Archiving Data
Create /root/data.tar.bz2 from /var/tmp

### Question 13: Password Expiry
Set new user password expiry to 20 days

### Question 14: Working with Strings
Copy lines containing 'wired' to /tmp/data

### Question 15: Simple Shell Script
Create mysearch script under /usr/local/bin
