# 💫 About Me:
💻 BTech CSE Student | Python<br>📚 Learning Data Structures & Algorithms<br>🏋️ Gym • 🍽️ Food • 🧠 Quiet mindset<br>Building skills one step at a time.<br>


## 🌐 Socials:
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/introvert.ix) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/shlokk09) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:lokhandeshlokk@gmail.com) 

# 💻 Tech Stack:
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=plastic&logo=c%2B%2B&logoColor=white) ![C](https://img.shields.io/badge/c-%2300599C.svg?style=plastic&logo=c&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=plastic&logo=python&logoColor=ffdd54) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=plastic&logo=html5&logoColor=white) ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=plastic&logo=microsoftazure&logoColor=white) ![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=plastic&logo=Flutter&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=plastic&logo=mongodb&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=plastic&logo=mysql&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=plastic&logo=figma&logoColor=white) ![Adobe](https://img.shields.io/badge/adobe-%23FF0000.svg?style=plastic&logo=adobe&logoColor=white) ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=plastic&logo=Canva&logoColor=white) ![Blender](https://img.shields.io/badge/blender-%23F5792A.svg?style=plastic&logo=blender&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=plastic&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=plastic&logo=github&logoColor=white) ![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=plastic&logo=gitlab&logoColor=white) ![Cypress](https://img.shields.io/badge/-cypress-%23E5E5E5?style=plastic&logo=cypress&logoColor=058a5e) ![Cisco](https://img.shields.io/badge/cisco-%23049fd9.svg?style=plastic&logo=cisco&logoColor=black) ![Riot Games](https://img.shields.io/badge/riotgames-D32936.svg?style=plastic&logo=riotgames&logoColor=white) ![Steam](https://img.shields.io/badge/steam-%23000000.svg?style=plastic&logo=steam&logoColor=white) ![nVIDIA](https://img.shields.io/badge/nVIDIA-%2376B900.svg?style=plastic&logo=nVIDIA&logoColor=white) ![AMD](https://img.shields.io/badge/AMD-%23000000.svg?style=plastic&logo=amd&logoColor=white) ![Epic Games](https://img.shields.io/badge/epicgames-%23313131.svg?style=plastic&logo=epicgames&logoColor=white) ![PlayStation Network](https://img.shields.io/badge/PSN-%230070D1.svg?style=plastic&logo=Playstation&logoColor=white) ![Meta](https://img.shields.io/badge/Meta-%230467DF.svg?style=plastic&logo=Meta&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=plastic&logo=notion&logoColor=white) ![CodeCov](https://img.shields.io/badge/codecov-%23ff0077.svg?style=plastic&logo=codecov&logoColor=white) ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=plastic&logo=nginx&logoColor=white)


### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=vetical&theme=merko)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=Shlokk09&limit=5&theme=shadow_blue&combine_all_yearly_contributions=true)

---
[![](https://visitcount.itsvg.in/api?id=Shlokk09&icon=2&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->







1- Navigate the Linux File System
pwd
ls
ls -l
ls -a
cd /
pwd && ls
cd /home
pwd && ls
cd /var
pwd && ls
cd /var/log
pwd && ls
cd ..
pwd
cd ~
pwd


2- Manage Files (Create, Copy, Delete, Search)
mkdir -p ~/linux_lab && cd ~/linux_lab
touch file1.txt file2.txt notes.txt
echo "Linux Operating System" > file1.txt
echo "Linux File Management" > file2.txt
echo "Linux commands are useful" > notes.txt
cat file1.txt
cp file1.txt file1_backup.txt
mv file2.txt linux.txt
grep "Linux" *.txt
find . -name "*.txt"
ls -l
rm file1_backup.txt
ls -l


3- View and Modify File Permissions
cd ~/linux_lab
touch permission.txt
ls -l permission.txt
whoami && id
chmod 640 permission.txt
ls -l permission.txt
sudo useradd student1 2>/dev/null; sudo groupadd students 2>/dev/null
sudo chown student1 permission.txt
ls -l permission.txt
sudo chgrp students permission.txt
ls -l permission.txt


4- Monitor Processes
ps
ps aux
ps -ef
ps aux | grep sshd
pidof sshd
top 


5- Kill Processes by PID or Name
sleep 300 &
jobs
ps -ef | grep sleep
kill <PID>
ps -ef | grep sleep
sleep 300 &
pkill sleep
ps -ef | grep sleep


6- Schedule Tasks with cron and at
sudo systemctl status crond
crontab -e
* * * * * date >> ~/cron_test.txt
crontab -l
sleep 65 && cat ~/cron_test.txt
at now + 2 minutes
atq


7- Create Users and Groups
sudo groupadd -f students
sudo useradd student2
sudo passwd student2
id student2
sudo usermod -aG students student2
groups student2
getent group students
su - student2
whoami && pwd
exit


8- Set Password Policies
sudo chage -l student1
sudo chage -M 90 student1
sudo chage -m 1 student1
sudo chage -W 7 student1
sudo chage -l student1
grep '^PASS' /etc/login.defs


9- Configure sudo Access
whoami && id
sudo visudo
sudo -l -U student1
sudo passwd student1
su - student1
sudo whoami
exit


10- Partition Disks using
lsblk
sudo fdisk /dev/sdb
sudo partprobe /dev/sdb
lsblk
sudo fdisk -l /dev/sdb


11- Manage LVM Volumes
sudo pvcreate /dev/sdb1
sudo pvs
sudo vgcreate labvg /dev/sdb1
sudo vgs
sudo lvcreate -L 1G -n lablv labvg
sudo lvs
lsblk
sudo lvresize -L +500M /dev/labvg/lablv
sudo lvs 


12- Mount Filesystems
sudo mkfs.xfs /dev/labvg/lablv
sudo mkdir -p /mnt/labdisk
sudo mount /dev/labvg/lablv /mnt/labdisk
findmnt /mnt/labdisk
df -h /mnt/labdisk
sudo umount /mnt/labdisk

UUID=<paste-uuid-here>  /mnt/labdisk  xfs  defaults  0 0

sudo systemctl daemon-reload
sudo mount -a
findmnt /mnt/labdisk


13- Configure SSH Key-Based Authentication
ip addr
ssh-keygen -t ed25519
ls -la ~/.ssh
ssh-copy-id student1@127.0.0.1
ssh student1@127.0.0.1
whoami
exit
chmod 700 ~/.ssh && chmod 600 ~/.ssh/id_ed25519 && chmod 644 ~/.ssh/id_ed25519.pub 


14- Manage Services using systemctl
sudo systemctl status sshd
sudo systemctl start sshd
sudo systemctl is-active sshd
sudo systemctl restart sshd
sudo systemctl enable sshd
sudo systemctl is-enabled sshd
sudo systemctl disable sshd
sudo systemctl status sshd
sudo systemctl enable --now sshd


15- Write a Bash Script to Automate Backups
mkdir -p ~/backup_demo/data ~/backup_demo/backups
echo "Important lab data" > ~/backup_demo/data/file.txt
cat ~/backup_demo/data/file.txt
cat << 'EOF' > ~/backup_demo/backup.sh
#!/bin/bash
mkdir -p ~/backup_demo/backups
tar -czf ~/backup_demo/backups/backup-$(date +%F-%H%M).tar.gz ~/backup_demo/data
echo "Backup completed successfully"
EOF
chmod +x ~/backup_demo/backup.sh
~/backup_demo/backup.sh
ls -lh ~/backup_demo/backups/*.tar.gz
du -sh ~/backup_demo/backups



