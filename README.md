# lisa.py
-An Exploit Dev Swiss Army Knife. 
-mona.py for Mac OS X

![alt tag](https://raw.githubusercontent.com/ant4g0nist/lisa.py/master/lisa.png)


#Usage:

Copy lisa.py and .lldbinit to ~/ 
Use the following commands:

	ant4g0nist$ cp lisa.py ~/lisa.py

	ant4g0nist$ cp .lldbinit ~/.lldbinit

	ant4g0nist$ lldb
	
(When a process crashes while debugging, run exploitable command to get the output)

#Output Looks like:
	(lisa)exploitable 
	is_exploitable = yes
	Crash accessing invalid address.

![alt tag](https://raw.githubusercontent.com/ant4g0nist/lisa.py/master/context.png)


(As of now, commiting exploitable command. Have to test the remaining code.)

Thanks:

	-Mona.py : https://github.com/corelan/mona

	-Crashwrangler : https://developer.apple.com/library/mac/technotes/tn2334/_index.html

	-Metasploit : https://github.com/rapid7/metasploit-framework
	
	-PEDA :	https://github.com/longld/peda
	
	-Phillips https://www.phillips321.co.uk/2013/04/02/recreating-pattern_create-rb-in-python/
