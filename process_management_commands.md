### top 
```sh
monitoring system performance in real time. It provides a dynamic view of the system’s processes, memory usage, CPU usage, and other system metrics.
```

### nice
``` sh
used to start a new process with a specific priority
syntax: nice -n <nice_value> <command>
example: nice -n 10 test.sh
test.sh have nice value 10
``` 

### renice
```sh
is used to change the nice value of an already running process
syntax: renice -n <nice_value> -p <pid>
ex: renice -n 0 -p <pid>
```
```sh
-20: Highest priority, most CPU time.(Danger)
0: Default priority.
19: Lowest priority, least CPU time.
```
