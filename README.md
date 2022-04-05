# Linux-commands

## VI
To leave editing mode press `ESC`.

| Command   | Description           |
| --------- | --------------------- |
| `i`       | insert before cursor  |
| `a`       | insert after cursor   |
| `A`       | insert at end of line |
| `o`       | new line below        |
| `O`       | new line above        |
| `u`       | undo                  |
| `.`       | repeat last command   |
| `yy`      | copy line             |
| `5yy`     | copy 5 lines          |
| `p`       | paste below           |
| `P`       | paste above           |
| `x`       | delete character      |
| `5x`      | delete 5 characters   |
| `dd`      | delete line           |
| `5dd`     | delete 5 lines        |
| `:10,20d` | delete lines 10-20    |
| `d0`      | delete to line begin  |
| `d$`      | delete to line end    |

**Navigation**

Navigate as usual with `arrow keys`, `home`, `end`, `pg up`, `pg dn`.

| Command | Description            |
| ------- | ---------------------- |
| `5G`    | go to line 5           |
| `H`     | go to top of screen    |
| `M`     | go to middle of screen |
| `L`     | go to end of screen    |
| `5w`    | move over 7 words      |
| `5b`    | move back 5 words      |

**Other**

| Command     | Description                  |
| ----------- | ---------------------------- |
| `/foo`      | search forward               |
| `?foo`      | search backwards             |
| `n`         | repeat search                |
| `:w`        | save                         |
| `:q`        | close                        |
| `:wq`       | save and close               |
| `:q!`       | close without saving         |
| `:!command` | run bash command             |
| `:r foo`    | read file foo into this file |
