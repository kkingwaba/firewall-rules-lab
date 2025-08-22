# firewall-rules-lab
Firewall rules lab using macOS Packet Filter (PF): blocked ping, allowed HTTP, and validated with live tests.
# Firewall Rules & Port Blocking Lab (macOS PF)

This project demonstrates configuring and testing firewall rules using the built-in Packet Filter (PF) firewall on macOS. The goal was to block ping (ICMP), allow HTTP traffic, and test results using real commands.

---

# Lab Steps
1. Backed up the default PF configuration file.
2. Wrote custom firewall rules (`myrules.conf`):
   - Block all ICMP (ping)
   - Allow HTTP (port 80)
   - Allow SSH (port 22)
3. Loaded and enabled PF with the new rules.
4. Tested results:
   - Ping (ICMP) blocked
   - HTTP traffic allowed
   - SSH attempted (connection refused since server not running)
5. Disabled PF and restored system to default settings.

---

# Screenshots
- Terminal with custom rules loaded
- Ping blocked (ICMP test)
- HTTP allowed (`curl http://example.com`)
- Firewall disabled after testing

---

# Skills Demonstrated
- macOS Firewall Configuration
- Packet Filtering with PF
- Basic Network Security Concepts
- Command Line Testing (ping, curl, ssh)
- Access Control Lists (ACLs)

---

# How This Applies
Firewall rule configuration and traffic testing are fundamental skills for IT support and security engineers. This lab demonstrates practical experience with controlling network access and verifying results in a Unix-based environment.
