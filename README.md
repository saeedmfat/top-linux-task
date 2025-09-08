# top-linux-task
## part 1
### 🔥 100 Linux & DevOps Challenges (Mid-level Focus)

🟢 Beginner (LPIC-1 fundamentals)

1. Install a Linux distribution (Debian/Ubuntu/CentOS) on a virtual machine.

2. Create 5 users with different groups and configure proper permissions.

3. Set file permissions using symbolic and numeric modes.

4. Configure sudo access for a user with limited privileges.

5. Practice navigating directories efficiently with relative/absolute paths.

6. Compress and extract files using tar, gzip, and bzip2.

7. Search inside files using grep with regular expressions.

8. Use find to locate files modified in the last 24 hours.

9. Create a bash alias and make it persistent across sessions.

10. Write a script to back up /etc into a timestamped archive.

🟡 Intermediate (Core Linux administration & LPIC-2 entry)

11. Configure static and dynamic IP addresses using netplan or ifcfg.

12. Add a persistent hostname and configure DNS resolution.

13. Set up an NTP client for time synchronization.

14. Install and configure the ssh service with key-based authentication.

15. Restrict root login over SSH and allow only specific users.

16. Configure a firewall using ufw or iptables.

17. Set resource limits for a user via /etc/security/limits.conf.

18. Create and schedule a cron job for daily log rotation.

19. Set up a systemd service for a custom script.

20. Monitor system logs in /var/log and identify failed login attempts.

🟠 Services & Networking

21. Configure Apache or Nginx to serve a static website.

22. Set up a virtual host with SSL/TLS enabled.

23. Configure a basic FTP server with restricted user access.

24. Install and configure a Samba share accessible from Windows.

25. Set up an NFS share between two Linux systems.

26. Configure a DHCP server and assign static leases.

27. Set up a local caching DNS server.

28. Configure Postfix as a local mail relay.

29. Restrict services with TCP wrappers or firewalld.

30. Analyze active network connections with ss and netstat.

🔵 Advanced System Administration

31. Write a bash script to monitor CPU, RAM, and disk usage.

32. Automate user creation from a CSV file with a shell script.

33. Configure rsyslog to send logs to a remote server.

34. Set up log rotation for custom applications.

35. Create a disk partition, format it, and mount it persistently.

36. Configure LVM with two disks and extend a logical volume.

37. Create a RAID 1 array using mdadm.

38. Encrypt a disk partition with LUKS.

39. Configure swap space using a file.

40. Implement quotas for users on a filesystem.

🟣 Security & Troubleshooting

41. Configure fail2ban to block repeated failed SSH logins.

42. Audit file access with auditd.

43. Use tcpdump to capture network packets for HTTP traffic.

44. Scan the system for open ports with nmap.

45. Identify and kill processes consuming high resources.

46. Analyze boot logs with journalctl.

47. Recover a forgotten root password from GRUB.

48. Restrict su access to specific users.

49. Secure shared memory using /etc/fstab options.

50. Harden SSH by changing port and disabling password login.

🔴 Realistic DevOps Scenarios (Mid-level)

51. Automate software installation with a shell script.

52. Write a script that checks service health and restarts if down.

53. Configure centralized user authentication with LDAP.

54. Deploy a simple web app with systemd and Nginx.

55. Set up SSH key forwarding for accessing multiple servers.

56. Configure rsync for incremental backups.

57. Write a script to check available updates and notify via email.

58. Monitor log files in real-time for errors with a script.

59. Configure a local yum/apt repository mirror.

60. Set up a PXE boot server for automated OS installation.

🟤 Scaling & Reliability

61. Configure HAProxy as a load balancer for two web servers.

62. Test high availability with keepalived (VRRP).

63. Benchmark system performance with stress and sysbench.

64. Optimize kernel parameters using sysctl.

65. Tune SSH connection limits for performance.

66. Configure a caching proxy with Squid.

67. Securely transfer large files between servers.

68. Implement centralized logging with ELK stack (basic).

69. Configure SNMP monitoring on a server.

70. Test disaster recovery by restoring from backup.

⚫ Expert-Level Linux Scenarios (Mid-level DevOps stretch)

71. Write a script to parse and visualize system logs.

72. Automate firewall rules deployment via a script.

73. Debug a system boot failure.

74. Configure chroot jail for a service.

75. Harden system by disabling unused kernel modules.

76. Analyze SELinux denials and fix them.

77. Configure AppArmor profiles for a service.

78. Use strace to debug a misbehaving process.

79. Set up a monitoring script for SSL certificate expiry.

80. Write a script to detect orphaned processes.

🟢 Final DevOps-Like Projects (Practical readiness)

81. Create a secure multi-user server environment.

82. Simulate a server migration from one host to another.

83. Write a script that provisions a server with users, firewall, and services.

84. Configure system resource monitoring with sar.

85. Set up remote logging with journald.

86. Implement basic configuration management with Ansible (optional Linux focus).

87. Optimize log rotation for high-traffic services.

88. Write a script to batch-manage multiple servers over SSH.

89. Build a system report generator (CPU, memory, uptime, users).

90. Securely wipe a disk for reuse.

🏆 Master-Level Linux Challenges (Mid-level DevOps engineer test)

91. Perform kernel upgrade and verify stability.

92. Debug a failed systemd service.

93. Configure IPv6 networking on a server.

94. Secure Nginx with rate limiting and headers.

95. Configure system auditing for compliance.

96. Investigate and mitigate a DoS attack on SSH.

97. Automate log analysis and anomaly detection.

98. Build a failover web service with two servers.

99. Simulate an incident and write a postmortem report.

## part 2

🔥 100 New Linux & Mid-level DevOps Challenges (No Duplicates)

🟢 Beginner (Foundations, LPIC-1 basics not repeated before)

100. Change the default shell for a user and test it.

101. Configure environment variables in .bashrc and .profile.

102. Create and manage hard links vs soft links.

103. Use cut, awk, and sed to extract data from a log file.

104. Write a simple shell script with command-line arguments.

105. Redirect both stdout and stderr to a file.

106. Use xargs with find to delete files.

107. Explore /proc filesystem to inspect system info.

108. Create and use a named pipe (FIFO).

109. Record command history and re-run specific commands with history.

🟡 Intermediate System Management

110. Configure persistent udev rules for a device.

111. Create a custom MOTD (message of the day).

112. Limit concurrent SSH sessions per user.

113. Write a shell script to rotate logs by size.

114. Configure an alias IP on a network interface.

115. Enable IP forwarding and test with two VMs.

116. Set a default gateway manually and test connectivity.

117. Analyze DNS queries with dig and host.

118. Configure persistent static routes.

119. Set up VLAN tagging on a Linux interface.

🟠 Services & Applications

120. Configure MariaDB/MySQL and create a user with restricted privileges.

121. Secure MySQL with mysql_secure_installation.

122. Deploy a basic PostgreSQL database and enable remote access.

123. Install and configure Redis, test persistence.

124. Configure Memcached and test with a client.

125. Run multiple websites on the same Apache instance.

126. Configure Nginx as a reverse proxy.

127. Create an HTTPS redirect in Apache or Nginx.

128. Enable HTTP/2 support in a web server.

129. Configure a mail server with Dovecot for IMAP access.

🔵 Storage & Filesystem Management

130. Create and manage loopback devices.

131. Format a partition with XFS and mount it.

132. Create an ext4 filesystem with journaling disabled.

133. Check filesystem consistency with fsck.

134. Resize a mounted filesystem online.

135. Benchmark disk I/O with fio.

136. Use du and ncdu to analyze disk usage.

137. Configure autofs for automatic mount.

138. Explore and configure overlay filesystems.

139. Create and manage a tmpfs mount.

🟣 Security & Access Control

140. Configure password aging and expiration policies.

141. Enforce account lockout after failed login attempts.

142. Configure PAM authentication to limit services.

143. Enable two-factor authentication with Google Authenticator for SSH.

144. Set up sudo rules for command whitelisting.

145. Audit failed login attempts using lastb.

146. Create a restricted shell for a specific user.

147. Configure iptables for port knocking.

148. Implement SSH bastion host access.

149. Restrict cron jobs to specific users.

🔴 Monitoring & Performance

150. Use htop and atop for live system monitoring.

151. Monitor network traffic with iftop.

152. Configure collectd to gather system metrics.

153. Write a script to alert when disk usage exceeds 80%.

154. Enable and analyze systemtap traces.

155. Monitor filesystem changes with inotifywait.

156. Measure memory usage of processes with smem.

157. Configure performance monitoring with dstat.

158. Analyze system boot time with systemd-analyze.

159. Set up an alert when load average exceeds a threshold.

🟤 Automation & Scripting

160. Write a script to validate IP addresses.

161. Create a menu-driven shell script for system tasks.

162. Write a script to batch-rename files with a specific pattern.

163. Automate SSH logins using expect.

164. Parse JSON output using jq in a script.

165. Create a backup script that only copies changed files.

166. Write a script that monitors services and sends desktop notifications.

167. Automate firewall rules based on IP lists.

168. Write a script that checks SSL certificates across multiple domains.

169. Create a script that extracts email addresses from a file.

⚫ Advanced Linux Administration

170. Configure kernel modules to load at boot.

171. Build and install a kernel from source.

172. Patch a kernel with a security update.

173. Enable and configure cgroups for resource control.

174. Explore and configure namespaces manually.

175. Set SELinux to enforcing mode and troubleshoot.

176. Configure SELinux boolean values for a web service.

177. Create a custom SELinux policy module.

178. Enable auditing for file deletions.

179. Write custom systemd unit dependencies.

🟢 Realistic Mid-level DevOps Scenarios

180. Configure SSH multiplexing for faster connections.

181. Simulate a disk failure and recover from LVM snapshot.

182. Write a script to clone system configuration files to another host.

183. Configure rsync over SSH with bandwidth limits.

184. Implement system update automation with unattended-upgrades.

185. Deploy a Git server on bare metal.

186. Set up Git hooks to trigger scripts after commits.

187. Configure SSH tunnels for forwarding local ports.

188. Synchronize time across multiple servers with Chrony.

189. Create a system inventory script reporting hostname, IP, and uptime.

🏆 Expert-Level Challenges

190. Configure multiple NIC bonding (active-backup, round-robin).

191. Troubleshoot packet loss using mtr.

192. Debug a misconfigured systemd service with dependencies.

193. Configure IPv6 firewall rules.

194. Harden Nginx with custom cipher suites.

195. Set up DNSSEC on a local DNS server.

196. Implement log forwarding to a Graylog server.

197. Configure auditbeat to send events to Elasticsearch.

198. Write a postmortem report for a simulated network outage.

199. Document a step-by-step server hardening guide for production readiness.

200. Document and harden a Linux production server as if it were ready for deployment.
