Fedora-System-Status-Dashboard (Google Code In task#3)
==============================
![ScreenCapture](https://raw.githubusercontent.com/seadog007/Fedora-System-Status-Dashboard/master/Screen.png)
How to use it?
------------------------------
1. Install these packages
```
yum install sysstat
yum install git
```
2. First, Clone it to your compter.
3. Use root to run these command
```
cd /
git init
```
4. And you need to add your "Important" files.
  - These are my files list
  ```
  git add /etc/passwd
  git add /etc/group
  git add /etc/shadow
  git add /home/seadog007/.ssh/authorized_keys
  git add /etc/httpd/conf*
  git add /etc/ssh/ssh*config
  git add /bin
  git add /etc/httpd/conf*
  git add /etc/fstab
  git add /etc/crontab
  git add /etc/yum.repos.d/
  git add /etc/gshadow*
  git add /etc/host*
  git add /etc/init.d/
  ```
5. Commit your files list.
`git commit -am "Your message"`
. And you need to run gen.sh with root
`./gen.sh`

6. You can view your machine status on the WEB!!
