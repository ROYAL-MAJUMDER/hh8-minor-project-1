PROJECT DESCRIPTION 

The Brute Force Detection System is a real-time security application that monitors authentication logs to detect repeated failed login attempts. When a brute-force attack is identified, the system automatically blocks the attacker’s IP address using firewall rules and displays attack details through a web-based monitoring dashboard.

 TOOLS USED 

The project uses Python for log parsing and attack detection, iptables for firewall-level IP blocking, Fail2Ban for automated intrusion prevention, SQLite for storing blocked IP records, and Flask for developing a web-based dashboard. Linux authentication logs serve as the primary data source for monitoring login activities.

HOW TO RUN THE PROJECT 

The project is executed on a Linux system. Authentication logs are monitored using Python scripts. Run the detection module with sudo to enable firewall blocking. 

 I LEARNED 

This project improved understanding of cybersecurity concepts such as brute-force attacks, intrusion detection, and firewall management. It provided hands-on experience with log analysis, Linux security tools, Python automation, database integration, and full-stack development using Flask, demonstrating how real-time security monitoring systems are designed and implemented.
