# grep and cut cmds:
to search through files for lines that contain a specific sequence of chars use grep
```sh
grep "search-value" <file_name>
```
```
bash git:(main) ✗ grep "firefighter" ff.dat
kris, firefighter, east naples
Frank, firefighter, north naples
john, firefighter, New york
(base) ➜  bash git:(main) ✗ grep "driver" ff.dat     
john, driver, east naples
Bob, driver, New York

```
- use 'cut' to filter data with the -d\ flag followed by what your separating by and the pipe to take out put from first command and -f1 for the first field like so:
```sh
grep "driver" ff.dat |cut -d\, -f1
``` 