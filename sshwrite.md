## SSH into VM walkthrough

1. Ensure ssh is active using the *netstat -natp* as well as *systemctl status ssh*
2. If not currently running use *systemctl start ssh* to activate ssh and ensure it is running wiht *systemctl status ssh*.
3. On the local machine use *ssh username@ipaddress* to connect via ssh. If IP address is unkwon use *ifconfig* on the VM to check IP.
4. to create a screened session use *screen -S main* and verify with *screen -ls*. 
