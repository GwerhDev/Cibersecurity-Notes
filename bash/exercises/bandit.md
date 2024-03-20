## Exercises

Taken from [overthewire.org](https://overthewire.org/wargames/bandit/)

``` bash
ssh bandit<level>@bandit.labs.overthewire.org -p 2220
```

password: bandit0

#### Level 0 -> 1
``` bash
cat readme
```

next_level_password: NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL

#### Level 1 -> 2

``` bash
cat ./-
```

next_level_password: rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi

#### Level 2 -> 3
``` bash
cat spaces\ in\ this\ filename
```

next_level_password: aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG

#### Level 3 -> 4
``` bash
cat inhere/.hidden
```

next_level_password: 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe

#### Level 4 -> 5
``` bash
file inhere/*
```

``` bash
find . -name -file07 | xatgs cat
```

next_level_password: lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR

#### Level 5 -> 6
``` bash
find inhere/* -type f -readable -size 1033c ! -executable | xargs cat | xargs
```

next_level_password: P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU

#### Level 6 -> 7
``` bash
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null | xargs cat
```

next_level_password: z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S

#### Level 7 -> 8
``` bash
grep "millionth" data.txt | awk '{print $2}'
```

next_level_password: TESKZC0XvTetK0S9xNwm25STk5iWrBvP

#### Level 8 -> 9

``` bash
cat data.txt | sort | uniq -u
```

next_level_password: EN632PlfYiZbn3PhVK3XOGSlNInNE00t