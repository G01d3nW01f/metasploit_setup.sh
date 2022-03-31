
# DBstatus is not connect 

  try press the below commands

```
$ msfconsole init
$ msfdb delete
$ msfdb init
$ cp /usr/share/metasploit-framework/config/database.yml /root/.msf4/
$ service postgresql restart
$ msfconsole
>db_status
```
