# sysmon
systemcheck (daily)
	starts
		hddtemps
		systemtemp
		disks
		kernel


systemcheckalert (each minute)
	starts
		systemtempalert ĉhecks temp on sensors in CHIPS, checks if
		hddtempsalert
		disksalert
		raidalert



# sysmon
