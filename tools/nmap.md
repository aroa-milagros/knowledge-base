# Nmap

## Purpose

Network discovery and security auditing.

## Basic Commands

### Scan a host

nmap 192.168.1.1

### Service detection

nmap -sV 192.168.1.1

### OS detection

nmap -O 192.168.1.1

## Useful Flags

| Flag | Description |
|--------|------------|
| -sS | SYN Scan |
| -sV | Service Version Detection |
| -O | OS Detection |
| -A | Aggressive Scan |

## Notes

- SYN Scan requires elevated privileges.
- Aggressive scan combines several techniques.
