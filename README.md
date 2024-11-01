# Hosts File IP Blocker

This Python script allows you to block and unblock IP addresses or domain names in the system's hosts file. It works by adding entries for specified IP addresses or domain names to redirect them to the loopback IP (127.0.0.1), effectively blocking them.

## Features

- **Block IPs or Domains**: Add entries to the hosts file to prevent access to specified IP addresses or domains.
- **Unblock IPs or Domains**: Remove entries from the hosts file to restore access to specified IP addresses or domains.
- **Automatic Check**: Before blocking, checks if an IP or domain is already blocked to avoid duplicate entries.
- **Error Handling**: Provides informative error messages for permission issues and other exceptions.

## Prerequisites

- **Python 3.6+**: This script requires Python 3.6 or higher.
- **Administrator Privileges**: Modifying the hosts file requires administrator or root privileges. 

## Installation

1. **Clone the repository**:
   ```bash
   git https://github.com/ZachVFXX/IpUtil.git
   cd IpUtil/src/
