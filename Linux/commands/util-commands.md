## Util commands

#### Change directory
``` bash
cd <route>
``` 

#### Print working directory
``` bash
pwd
``` 

#### List
``` bash
ls <route>
```

| Parameter  | Description            |
| ---------- | ---------------------- |
| -a         | All                    |
| -l         | Long listing format    |
| -R         | Recursive              |

#### Create empty file
``` bash
touch
```

| Parameter  | Description                  |
| ---------- | ---------------------------- |
| -a         | change access hour           |
| -m         | change modification date     |

#### Copy
``` bash 
cp <origin_route> <destiny_route>
```

| Parameter  | Description                   |
| ---------- | ----------------------------- |
| -i         | confirmation if already exist |
| -r         | copy directories              |

#### Move
``` bash 
mv <origin_route> <destiny_route>
```

| Parameter  | Description                   |
| ---------- | ----------------------------- |
| -i         | confirmation before move      |
| -u         | rewrite older                 |

#### Remove
``` bash 
rm <route>
```

| Parameter  | Description                   |
| ---------- | ----------------------------- |
| -i         | confirmation before remove    |
| -r         | remove directories            |

#### Make directory
``` bash 
mkdir <directory_route>
```

| Parameter  | Description                   |
| ---------- | ----------------------------- |
| -p         | father directory              |

#### Delete directory (empty directory only)
``` bash 
rmdir <directory_route>
```

#### Concatenate (read files into terminal)
``` bash 
cat <file_route>
```
| Parameter  | Description                   |
| ---------- | ----------------------------- |
| -n         | number of lines               |

