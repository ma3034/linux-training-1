# grep command

- Example1
```
[eric@rhel9 linux-training-1]$ grep manu /etc/passwd
manu:x:1001:1001::/home/manu:/bin/bash
[eric@rhel9 linux-training-1]$
```


- Example2
```
[eric@rhel9 linux-training-1]$ grep -e manu -e root /etc/passwd
root:x:0:0:root:/root:/bin/bash
operator:x:11:0:operator:/root:/sbin/nologin
manu:x:1001:1001::/home/manu:/bin/bash
[eric@rhel9 linux-training-1]$
```

