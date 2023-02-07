# Check VMware SLP service
Check and stop the VMware SLP service on VMware ESXi hosts which is actively used for ransomware attacks.

## PowerCLI Script overview

The PowerCLI Script will run against the vCenter Server environment:

- Pull a list of ESXi hosts
- Check the hosts for the SLP service enabled and running
- Output the names of hosts where it is running
- Output the names of hosts where it is not running
- If the host is running SLP service 
