How to Run and Test It
To test this safely without needing a live cloud server, you can set up a local testing environment:
1. Spin up a RHEL 10 Virtual Machine on your Mac.
2. Purposely fail the login to your VM via SSH a few times to generate logs in ⁠/var/log/secure⁠.
3. Run the script as the root user: ⁠sudo python3 auth_monitor.py⁠
4. Verify the firewall rule was added by running: ⁠sudo firewall-cmd --list-all⁠
