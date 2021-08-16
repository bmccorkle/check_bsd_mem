# check_bsd_mem
Monitoring Plugin to check Memory Usage on a FreeBSD Server 

This script checks memory usage and optionally verifies if the used memory
is ABOVE defined threshhold from Avail Memory (See DEFINITIONs)

	OPTIONS:

	-h   Help
	-c   CRIT: Used Memory in MB or Percent (end with %)
	-w   WARN: Used Memory in MB or Percent (end with %)
	-p   Additional Perf Data to Record.  Combine as needed
	     (a)ctive, (i)nactive, (w)ired, (f)ree, (c)ache
	-r   Additional Return Msg items to Display.  Combine as needed
	     (a)ctive, (i)nactive, (w)ired, (f)ree, (c)ache
	     * Multiline.  Only visible under service details *
	-u   UNITS: [MB] [GB] (Default: MB)
	-V   Version
