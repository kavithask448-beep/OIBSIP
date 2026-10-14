# Task 2: Basic Firewall Configuration with UFW

## 1. Objective
To configure a firewall using UFW (Uncomplicated Firewall) on Ubuntu Linux and understand how it controls network traffic.

## 2. Tools Used
- Operating System: Ubuntu 24.04
- Environment: Oracle VirtualBox
- Firewall Tool: UFW 0.32.6
- Terminal: Ubuntu Terminal

## 3. Firewall Configuration
The following commands were used:

```bash
sudo ufw status
sudo ufw version
sudo ufw default deny incoming
sudo ufw default allow outgoing
sudo ufw enable
sudo ufw status verbose
```

## 4. Results
The firewall was successfully enabled.

- Firewall Status: Active
- Logging: On (low)
- Incoming Traffic: Denied by default
- Outgoing Traffic: Allowed by default
- Routed Traffic: Disabled

## 5. Security Benefits
- Helps block unwanted incoming connections.
- Allows outgoing connections by default.
- Provides basic firewall logging.
- Helps improve network security.

## 6. Conclusion
This task provided practical experience configuring and verifying a firewall using UFW on Ubuntu Linux.
