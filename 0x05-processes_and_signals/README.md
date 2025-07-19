# 0x05-processes_and_signals

This directory contains solutions to the "0x05-processes_and_signals" project tasks as part of the system_engineering-devops curriculum.

## Project Overview

This project provides an introduction to Linux processes and signals. It covers the basics of managing process lifecycles, monitoring running processes, and using signals to control process behavior. Through hands-on tasks, learners practice identifying process IDs, using commands to manipulate processes, and handling signals to start, stop, and modify processes.

## Tasks Included

* **0. What Is My PID?**: Script to display its own Process ID.
* **1. List Your Processes**: Script to display a comprehensive list of all running processes with hierarchy.
* **2. Show Your Bash PID**: Script to filter processes and show only `bash` related lines (without `pgrep`).
* **3. Show your Bash PID Made Easy**: Script to display PID and process name for `bash` processes (without `ps`).
* **4. To Infinity and Beyond**: Script that runs an infinite loop displaying a message and pauses.
* **5. Don't Stop Me Now!**: Script to stop the `4-to_infinity_and_beyond` process using `kill`.
* **6. Stop Me if You Can**: Script to stop the `4-to_infinity_and_beyond` process using an alternative method (not `kill` or `killall`).
* **7. Highlander**: Script that displays a message indefinitely and handles `SIGTERM` without terminating, and a separate script to send `SIGTERM` to it.
* **8. Beheaded Process**: Script to forcibly kill the `7-highlander` process using `SIGKILL`.

## How to Use

Each task is a standalone Bash script. To run them:

1.  Navigate to the `0x05-processes_and_signals` directory.
2.  Make the script executable: `chmod u+x <script_name>` (e.g., `chmod u+x 0-what-is-my-pid`)
3.  Execute the script: `./<script_name>` (e.g., `./0-what-is-my-pid`)

*Note: Some tasks require running multiple scripts concurrently in different terminal windows for testing (e.g., Tasks 4, 5, 6, 7, 8).*

## Author

[Tajudeen Bawumia]
