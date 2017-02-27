## uname

### **uname** stands for unix name. uname is used to get the information of operating system (linux / unix) running on a machine.

#### Example

My system is running on Debian, so output from **uname -a** (a stands for all) command looks like as follows :

```sh
Linux surendra 3.16.0-4-amd64 #1 SMP Debian 3.16.7-ckt20-1+deb8u3 (2016-01-17) x86_64 GNU/Linux
```

Following table will give the more information about uname command.

|Command|Description|Example output|
|-------|-----------|--------------|
|uname -a| Gives all the available information about the operating system | Linux surendra 3.16.0-4-amd64 #1 SMP Debian 3.16.7-ckt20-1+deb8u3 (2016-01-17) x86_64 GNU/Linux|
|uname -s| Gives kernel name | Linux |
|uname -r| Gives kernel release | 3.16.0-4-amd64 |
|uname -v| Gives kernel version | #1 SMP Debian 3.16.7-ckt20-1+deb8u3 (2016-01-17) |
|uname -m| Gives whether the operating system is 32 bit or 64 bit | x86_64 |
|uname -o| Gives operating system | GNU/Linux |

**Note:** `uname --help` command will give more information about usage of uname command.
