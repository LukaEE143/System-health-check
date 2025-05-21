# System Health Audit Script

## Task Description

You're tasked with creating a script that audits a Linux machine (Ubuntu 20.04+) for key health
and performance indicators. It must execute system checks, and generate a clear and concise
report in .txt format.

Requirements:
- CPU usage (PASS if < 10%)
- Memory usage (PASS if > 500MB free)
- Disk usage (/ partition PASS if < 80%)
- List running systemd services
