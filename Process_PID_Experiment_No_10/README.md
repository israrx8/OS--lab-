# Process PID Experiment No. 10

## Aim
To write and execute a C program to display the current Process ID (PID) and Parent Process ID (PPID).

## Program
The program uses the `getpid()` function to obtain the current process ID and `getppid()` to obtain the parent process ID.

## Source File
- `tree.c`

## Compile
```bash
gcc tree.c -o tree
```

## Run
```bash
./tree
```

## Output
The PID values change each time the program is executed.

Example:
```text
Current PID: 12345
Parent PID: 12340
```

## Result
The C program was successfully compiled and executed, and the current PID and parent PID were displayed.
