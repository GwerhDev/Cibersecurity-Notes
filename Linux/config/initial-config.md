## First steps

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

#### Language config

Open configuration for locales
``` bash
sudo dpkg-reconfigure locales
```

Then, unselect current language and select your language with "space" key. 

Finally, reboot:
``` bash
reboot
```

#### Keyboard config

Go to "Settings Manager", select "Keyboard" and then "Layout" tab.

