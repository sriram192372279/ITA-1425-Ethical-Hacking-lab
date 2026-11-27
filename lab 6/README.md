# Lab 6: Kali Linux Commands: touch, pwd, wget

## Commands / Code

```bash
# i) touch - create an empty file
touch file1.txt
ls -l file1.txt

# ii) pwd - print working directory
pwd

# iii) wget - download a file from the web
wget https://example.com/index.html
```

## Expected Output

```text
┌──(kali㉿kali)-[~/lab6]
└─$ touch file1.txt && ls -l file1.txt
-rw-r--r-- 1 kali kali 0 Nov 27 18:11 file1.txt

┌──(kali㉿kali)-[~/lab6]
└─$ pwd
/home/kali/lab6

┌──(kali㉿kali)-[~/lab6]
└─$ wget https://example.com/index.html
--2026-11-27 18:11:02--  https://example.com/index.html
Resolving example.com... 93.184.216.34
HTTP request sent, awaiting response... 200 OK
Length: 1256 (1.2K) [text/html]
Saving to: 'index.html'
index.html          100%[===================>]   1.23K  --.-KB/s    in 0s
```

## Output Image

![Output](output.png)
