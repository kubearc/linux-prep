# RHCSA (EX200) – Questions Only

---

## NODE 1

### Question 1: Networking Configuration

Configure the system with the following details:

* IP Address: 172.25.10.11
* Subnet Mask: 255.255.255.0
* Default Gateway: 172.25.10.254
* Nameserver: 172.25.254.254
* Hostname: primary.netX.example.com

---

### Question 2: Yum Repository Configuration

Configure yum repositories using the following URLs:

* [http://content.example.com/rhel9/x86_64/dvd/BaseOS](http://content.example.com/rhel9/x86_64/dvd/BaseOS)
* [http://content.example.com/rhel9/x86_64/dvd/AppStream](http://content.example.com/rhel9/x86_64/dvd/AppStream)

---

### Question 3: SELinux Debugging

The httpd service must run on port 82.

* Web content is located in /var/www/html
* Content should be accessible using:
  curl localhost:82/file1
* Output should be:
  "Welcome to the EX200 Exam!"
* Service must start automatically at boot

---

### Question 4: Cron Jobs

Configure cron jobs for user `natasha`:

* Run `/bin/echo hello` daily at 13:30
* Run `/bin/echo new1` every 3 minutes

---

### Question 5: Users and Groups

Create the following:

* Group: sysadmin
* User ryan (secondary group: sysadmin)
* User sarah (secondary group: sysadmin)
* User harry (no interactive shell, not in sysadmin group)
* Password for all users: atenorth

---

### Question 6: Collaborative Directory

Create `/common/admin` with:

* Group ownership: sysadmin
* Access only for sysadmin members
* Files created should inherit group ownership automatically

---

### Question 7: NTP Configuration

Configure the system as an NTP client of:
utility.domain0.example.com

---

### Question 8: Find Command

Find all files owned by user `simone` and copy them to:
/root/found

---

### Question 9: AutoFS Configuration

Configure autofs for user `remoteuser5`:

* NFS server: node1.domain5.example.com
* Export: /rhome/remoteuser5
* Only this home directory should be accessible
* Home directory must be writable

---

### Question 10: Specific UID User

Create a user `james` with:

* UID: 2112
* Password: sestiver

---

### Question 11: Sudo Privileges

Grant passwordless sudo access to group `elite`

---

### Question 12: Archiving

Create a bzip2 compressed archive:

* Backup /var/tmp to /root/data.tar.bz2

---

### Question 13: Password Expiry

Set password expiry for all new users to 20 days

---

### Question 14: Working with Strings

Copy all lines containing the word `wired` from:
/usr/share/dict/words
to:
/tmp/data

---

### Question 15: Shell Script

Create a script `mysearch` that:

* Lists files under /usr
* Size less than 10MB
* Have SGID permission
* Saves output to /root/search_file
* Script location: /usr/local/bin

---

### Question 16: Login Application

Configure a setup so that when user `albert` logs in, the following message is displayed:
"Welcome to the EX200 Exam"

---

### Question 17: Container Image

As user `Andrew`, build a container image named `watcherimage` using:
[http://server1.net3.example.com/materials/3/Containerfile](http://server1.net3.example.com/materials/3/Containerfile)

---

### Question 18: Container as Service

Create a container with the following requirements:

* User: Andrew
* Image: watcherimage
* Container name: my-watcher
* Mounts:

  * /opt/files → /opt/incoming
  * /opt/processes → /opt/outgoing
* Configure as a systemd service
* Service must start at boot

---

## NODE 2

### Question 1: Password Recovery

Reset the root password of Node 2 to:
redhat

---

### Question 2: Yum Repository Configuration

Configure yum repositories using:

* [http://content.example.com/rhel9/x86_64/dvd/BaseOS](http://content.example.com/rhel9/x86_64/dvd/BaseOS)
* [http://content.example.com/rhel9/x86_64/dvd/AppStream](http://content.example.com/rhel9/x86_64/dvd/AppStream)

---

### Question 3: Tuned Profile

Set the recommended tuning profile for the system

---

### Question 4: Swap Partition

Create a 250MB swap partition and make it persistent across reboots

---

### Question 5: LVM Creation

Create an LVM setup with:

* Volume Group: myvol
* PE size: 8MB
* Logical Volume: mydatabase
* Size: 50 PE
* Filesystem: ext3
* Mount point: /database (persistent)

---

### Question 6: Resize LVM

Resize the logical volume `home` to 150MiB

---
