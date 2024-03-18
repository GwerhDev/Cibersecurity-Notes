## First steps ##

#### Terminator

Install terminator from console:

```
sudo apt install terminator
```

run it:

```
terminator
```

#### Bash

Change shell to bash temporally:
```
/bin/bash
```

Change shell to bash permanently:
```
chsh -s /bin/bash
```

#### Keyboard config

Change keyboard language to spanish temporally:
``` bash
setxkbmap es sundeadkeys
```

Change keyboard language to spanish permanently:
``` bash
sudo dpkg-reconfigure locales
```

Then, unselect current language and select spanish language with "space" key. 

Finally, reboot:
``` bash
reboot
```