# Day 5 - Processes

## What I learned

Today I learned how processes work in Linux and how to manage them.

------------------------------------------------------------------------

## What is a process

A process is a running program in the system.

Examples:
- terminal
- browser
- script

------------------------------------------------------------------------

## Viewing processes

Commands:
```bash
ps
ps aux
```

- `ps` shows processes in the current session
- `ps aux` shows all running processes

------------------------------------------------------------------------

## Monitoring processes

Command:
```bash
top
```

- shows real-time system usage
- displays CPU and memory usage
- updates continuously

------------------------------------------------------------------------

## Process ID (PID)

Each process has a unique ID called PID.

Example:
```bash
ps aux | grep bash
```

------------------------------------------------------------------------

## Killing processes

Command:
```bash
kill PID
```

Force kill:
```bash
kill -9 PID
```

------------------------------------------------------------------------

## Summary

Day 5 helped me understand how to view, monitor, and stop processes in Linux.
