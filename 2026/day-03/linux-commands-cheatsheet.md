Ycreating  a cheat sheet of commands focused on:

- Process Management
    ps aux - Display all running processes with detailed information.
    top - Monitor real-time CPU, memory, and process usage.
    htop - Interactive process viewer with easier navigation than top.
    kill -9 PID - Forcefully terminate a process using its PID.
    pkill process_name - Kill processes by process name instead of PID.
    systemctl status service - Check the status of a systemd service.
    journalctl -u service - View logs for a specific systemd service.
    nohup command & - Run a process in the background even after logout.\

- File System Management
    ls -lah - List files with permissions, sizes, and hidden files.
    df -h - Show disk space usage in human-readable format.
    du -sh directory - Check total size of a directory.
    find /path -name file - Search for files and directories by name.
    chmod 755 file - Change file permissions.
    chown user:user file - Change file ownership.
    tar -czvf backup.tar.gz dir - Compress files/directories into a tar archive.
    rsync -av source/ dest/ - Sync files/directories efficiently between systems.

- Networking
    ping host - Check network connectivity to a host.
    curl URL - Send HTTP requests and test APIs/web services.
    wget URL - Download files from the internet via CLI.
    ss -tulnp - Display listening ports and active network connections.
    ip a - Show IP addresses and network interfaces.
    netstat -tulnp - View open ports and network statistics (legacy but common).
    traceroute host - Trace the network path to a destination host.
    nslookup domain - Query DNS records for a domain.

- Troubleshooting
    tail -f logfile - Monitor logs in real time.
    grep "error" logfile - Search logs or files for specific patterns/errors.
    free -h - Check RAM and swap memory usage.
    uptime - Show system uptime and load average.
    dmesg - Display kernel and hardware-related logs.
    iostat - Monitor CPU and disk I/O performance.
    vmstat - Show system performance statistics.
    lsof -i :PORT - Find which process is using a specific port.