# Basic Network Scanning with Nmap

## Objective

The objective of this task is to perform a basic network scan using Nmap and identify open ports, services, and operating system information on a local system.

## Tools Used

- Nmap 7.991
- Windows Command Prompt
- Windows 10

## Target

127.0.0.1 (localhost)

The scan was performed only on the local computer.

## Scans Performed

### 1. Basic Network Scan

Command:

nmap 127.0.0.1

This scan identified open and closed TCP ports on the local system.

### 2. Service Version Detection

Command:

nmap -sV 127.0.0.1

This scan attempted to identify the services and their versions running on open ports.

### 3. Operating System Detection

Command:

nmap -O 127.0.0.1

This scan identified the operating system information of the local system.

## Results

The scan identified the following open ports:

| Port | State | Service |
|------|-------|---------|
| 135/tcp | Open | MSRPC |
| 445/tcp | Open | Microsoft-DS |
| 7070/tcp | Open | RealServer |

The OS detection identified the system as Microsoft Windows 10.

A total of 997 TCP ports were reported as closed.

## Security Considerations

- Open ports should be reviewed to determine whether the associated services are required.
- Unnecessary services should be disabled where appropriate.
- Firewall rules should restrict access to services that do not need to be publicly accessible.
- Service identification should be verified before making security decisions.

## Ethical Use

Nmap should only be used on systems that you own or have permission to test.

This project was performed on the local computer using 127.0.0.1.

## Files Included

- nmap_scan_results.txt
- README.md
- Screenshots of scan results