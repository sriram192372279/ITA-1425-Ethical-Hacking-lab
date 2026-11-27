# Lab 3: Kali Linux Commands: tree, head, tail

## Commands / Code

```bash
# 1. tree command - display directory hierarchy
tree /var/log/apt

# 2. head command - display first 5 lines of a file
head -n 5 /etc/passwd

# 3. tail command - display last 5 lines of a file
tail -n 5 /etc/passwd
```

## Expected Output

```text
┌──(kali㉿kali)-[~/lab3]
└─$ tree /var/log/apt
/var/log/apt
├── eipp.log.xz
├── history.log
└── term.log

0 directories, 3 files

┌──(kali㉿kali)-[~/lab3]
└─$ head -n 5 /etc/passwd
root:x:0:0:root:/root:/usr/bin/zsh
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync

┌──(kali㉿kali)-[~/lab3]
└─$ tail -n 5 /etc/passwd
_rpc:x:115:65534::/run/rpcbind:/usr/sbin/nologin
statd:x:116:65534::/var/lib/nfs:/usr/sbin/nologin
kali:x:1000:1000:Kali,,,:/home/kali:/usr/bin/zsh
```

## Output Image

![Output](output.png)
