# sysmon, monitor several values and send an email if triggered
systemcheck (daily)
	starts
		hddtemps
		systemtemp
		disks
		kernel
		
	sends mail with summary


systemcheckalert (each minute)
	starts
		systemtempalert
		hddtempsalert
		disksalert
		raidalert
		
	sends email if triggered (beware! spams!)
	
first shell scripting attempt. kinda embarrasing. left here for 'historic' reasons :P
