Bash Service Health Monitor

Overview
This project is a Bash script that monitors services on Linux. It checks if services are running, restarts them if needed, logs the results, and shows a summary.

Features

Reads services from services.txt
Checks status using systemctl
Restarts failed services
Logs output to /var/log/health_monitor.log
Shows summary (Total, Healthy, Recovered, Failed)
Supports --dry-run mode

How to Run
chmod +x monitor.sh
sudo ./monitor.sh

Dry Run
./monitor.sh --dry-run

Example Output
Checking services...
ssh is running

===== SUMMARY =====
Total Services: 1
Healthy: 1
Recovered: 0
Failed: 0

Author
Harshita Digari
