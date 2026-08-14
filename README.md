# ⌚ Digital Watch using Bash Script

A simple **Digital Watch** created using a Bash shell script.  
The script displays the current system time in the terminal and updates it every second.

## 📌 Project Overview

This project demonstrates how Bash scripting can be used to create a simple real-time digital clock.

The script:
- Displays the current time
- Updates the time every second
- Clears the terminal before displaying the updated time
- Uses ANSI escape codes to display the time in red color
- Runs continuously until stopped by the user

## 🛠️ Technologies Used

- Linux
- Bash Shell Scripting
- Terminal
- `date` command
- `clear` command
- `sleep` command

## 📂 Project Structure

```text
digital_watch/
│
├── digital_watch.sh
└── README.md
````

## 💻 Script

```bash
#!/bin/bash

RED='\e[1;31m'

while true
do
    clear
    echo -e "${RED}$(date +%T)"
    sleep 1
done
```

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/komalagale4/Digital-Watch.git
```

### 2. Go to the Project Directory

```bash
cd digital_watch
```

### 3. Give Execute Permission

```bash
chmod +x digital_watch.sh
```

### 4. Run the Script

```bash
./digital_watch.sh
```

## 🕒 Output

The terminal displays the current time in the following format:

```text
15:30:45
```

The time automatically updates every second.

## 🛑 Stop the Digital Watch

Press:

```text
Ctrl + C
```

to stop the script.

## 📚 Bash Concepts Used

* Variables
* Infinite `while` loop
* Command substitution `$(...)`
* ANSI color codes
* `date` command
* `clear` command
* `sleep` command
* File permissions

## 🎯 Learning Objective

The main objective of this project is to understand the basics of **Bash scripting**, loops, variables, Linux commands, and real-time terminal output.

## 👩‍💻 Author

**Komal Agale**

 Linux | AWS | DevOps | Bash Scripting
