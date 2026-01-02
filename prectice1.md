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
- http://content.example.com/rhel8.0/x86_64/dvd/BaseOS
- http://content.example.com/rhel8.0/x86_64/dvd/AppStream

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
