# Server Performance Stats

A simple Bash script to monitor basic Linux server performance.

## Features

* CPU usage
* Memory usage (Used, Free, Percentage)
* Disk usage (Used, Free, Percentage)
* Top 5 processes by CPU usage
* Top 5 processes by memory usage
* OS, uptime, load average, and logged-in users

## Requirements

* Linux / WSL
* Bash
* `bc`

Install `bc` if required:

```bash
sudo apt update
sudo apt install bc
```

## Run the Project

Clone the repository:

```bash
git clone https://github.com/khushizz/Performance-Server-Stats.git
```

Go to the project:

```bash
cd server-stats
```

Give execute permission:

```bash
chmod +x server-stats.sh
```

Run the script:

```bash
./server-stats.sh
```

Or:

```bash
bash server-stats.sh
```
