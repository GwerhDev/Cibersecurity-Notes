## Exercises

Taken from [overthewire.org](https://overthewire.org/wargames/bandit/)

``` bash
ssh bandit<level>@bandit.labs.overthewire.org -p 2220
```
| initial level password |
| ---------------------- |
| bandit0                |

#### Level 0 -> 1
``` bash
cat readme
```

| next level password              |
| -------------------------------- |
| NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL |

#### Level 1 -> 2

``` bash
cat ./-
```

| next level password              |
| -------------------------------- |
| rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi |

#### Level 2 -> 3
``` bash
cat spaces\ in\ this\ filename
```

| next level password              |
| -------------------------------- |
| aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG |

#### Level 3 -> 4
``` bash
cat inhere/.hidden
```

| next level password              |
| -------------------------------- |
| 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe |

#### Level 4 -> 5
``` bash
file inhere/*
```

``` bash
find . -name -file07 | xatgs cat
```

| next level password              |
| -------------------------------- |
| lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR |

#### Level 5 -> 6
``` bash
find inhere/* -type f -readable -size 1033c ! -executable | xargs cat | xargs
```

| next level password              |
| -------------------------------- |
| P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU |

#### Level 6 -> 7
``` bash
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null | xargs cat
```

| next level password              |
| -------------------------------- |
| z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S |

#### Level 7 -> 8
``` bash
grep "millionth" data.txt | awk '{print $2}'
```

| next level password              |
| -------------------------------- |
| TESKZC0XvTetK0S9xNwm25STk5iWrBvP |

#### Level 8 -> 9

``` bash
cat data.txt | sort | uniq -u
```

| next level password              |
| -------------------------------- |
| EN632PlfYiZbn3PhVK3XOGSlNInNE00t |

#### Level 9 -> 10

``` bash
contador=1 strings data.txt | grep "===" | while read line; do echo "Line $contador": $line; let contador+=1; done | awk 'NR==4' | awk 'NF{print $NF}'
```

| next level password              |
| -------------------------------- |
| G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s |

#### Level 10 -> 11 

``` bash
cat data.txt | base64 -d | awk 'NF{print $NF}'
```

| next level password              |
| -------------------------------- |
| 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM |

#### Level 11 -> 12

``` bash
cat data.txt | tr '[G-ZA-Fg-za-f]' '[T-ZA-St-za-s]' | awk 'NF{print $NF}'
```

| next level password              |
| -------------------------------- |
| JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv |

#### Level 12 -> 13

``` bash

```

| next level password              |
| -------------------------------- |
|  |

#### Level 13 -> 14

``` bash

```

| next level password              |
| -------------------------------- |
|  |

#### Level 14 -> 15

``` bash

```

| next level password              |
| -------------------------------- |
|  |

#### Level 15 -> 16

``` bash

```

| next level password              |
| -------------------------------- |
|  |

#### Level 16 -> 17

``` bash

```

| next level password              |
| -------------------------------- |
|  |

#### Level 17 -> 18

``` bash

```

| next level password              |
| -------------------------------- |
|  |

#### Level 18 -> 19

``` bash

```

| next level password              |
| -------------------------------- |
|  |

#### Level 19 -> 20

``` bash

```

| next level password              |
| -------------------------------- |
|  |