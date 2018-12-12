| Command               | Syntax                                                      	| Method of Execution 	| More Info |
|-----------------------|---------------------------------------------------------------|-----------------------|-----------|
| browserpivot		  	| browserpivot [pid] [x86\|x64]								| 					  	| HERE      |
| bypassuac				| bypassuac [listener]											| DLL				  	| HERE		|
| cancel				| cancel [\*file\*]												|					  	| HERE 	  	|
| cd 					| cd [directory]												| 					  	| HERE  	|
| checkin 				| checkin 														|   				  	| HERE      |
| clear					| clear 														| 					  	| HERE  	|
| covertvpn 			| covertvpn [interface] [ip address]							|					  	| HERE 	  	|
| cp 					| cp [source file ] [dst file]									|  					  	| HERE 	  	|
| dcsync				| dcsync [domain.fqdn] [domain\user]							| 					  	| HERE      |
| desktop 				| desktop [pid] [x86\|x64] [high`|`low]						| Injects VNC Serer	  	| HERE 	  	|
| dllinject 			| dllinject [pid] [/path/to/my.dll]								|					  	| HERE      |
| dllload 				| dllload [pid] [C:\path\to\my.dll]								| LoadLibrary()	API	  	| HERE 	  	|
| download	 			| download [file]												|					  	| HERE  	|
| downloads 			| downloads													    |					  	| HERE 		|
| drives				| drives														|						| HERE 		|
| elevate				| elevate [exploit] [listener]									| 						| HERE 		|
| execute 				| execute [program] [args]										|						| HERE 		|
| execute-assembly		| execute-assembly [path/to/file.exe] [args]					| CLR in temp process	| HERE		|
| exit 					| exit 															|						| HERE		|
| getprivs				| getprivs														|						| HERE		|
| getsystem				| getsystem														| 						| HERE		|
| getuid				| getuid														|						| HERE		|
| hashdump				| hashdump														| LSASS Injection		| HERE		|
| help					| help \| help [command]										|						| HERE		|
| inject 				| inject [pid] <x86`|`x64> [listener]							| Process Injection 	| HERE		|
| jobkill				| jobkill [job id]												|						| HERE 		|
| jobs					| jobs															|						| HERE 		|
| kerberos_ccache_use	| 																|						| HERE 		|
| kerberos_ticket_purge | kerberos_ticket_purge 										| 						| HERE		|
| kerberos_ticket_use	| kerberos_ticket_use [/path/to/ticket.ticket]					| 						| HERE		|
| keylogger				| keylogger [pid] <x86\|x64>									| Process Injection 	| HERE 		|			
| kill 					| kill [pid]													| 						| HERE 		|
| link 					| link [ip address]												| 						| HERE 		|
| logonpasswords 		| logonpasswords												| MimiKatz				| HERE 		|
| ls 					| ls [folder]													| 						| HERE 		|
| make_token			| make_token [domain\username] [password]						| 						| HERE 		|
| mimikatz 				| mimikatz [module::command] <args>								| MimiKatz 				| HERE 		|
| mkdir 				| mkdir [folder]												| 						| HERE 		|
| mode 					| mode <dns\|dns-txt\|dns6\|http\|smb>						|						| HERE 		|
| mv					| mv [source file] [dst file]									| 						| HERE 		|
| net 					| net [command][arguments]										|						| HERE 		|
| note					| note [text]													|						| HERE 		|
| portscan				| portscan [targets][ports][arp\|icmp\|none][max connections]	| Process Injection 	| HERE 		|
| powerpick				| powerpick [cmdlet] [args]										|						| HERE 		|
| powershell			| powershell [cmdlet] [args]									| PowerShell 			| HERE 		|
| powershell-import		| powershell-import [/path/to/script.ps1]						| PowerShell 			| HERE  	|
| ppid 					| ppid [pid]													|						| HERE 		|
| ps 					| ps 															| Win32 APIs			| HERE 		|
| psexec				| psexec [host] [share] [listener] 								| Drops .exe to disk 	| HERE 		|
| psexec_psh			| pshexec_psh [host] [listener]									| PowerShell 			| HERE 		|
| psinject				| psinject [pid] [arch] [cmdlet] [args]							| Process Injection		| HERE 		|
| pth 					| pth [domain\user] [NTLM Hash]									| MimiKatz 				| HERE 		|
| pwd 					| pwd 															| 						| HERE 		|
| reg 					| reg query [x86\|x64] [root\path]								|						| HERE 		|
| rev2self				| rev2self														| 						| HERE 		|
| rm 					| rm [folder]													| 						| HERE 		|
| rportfwd				| rportfwd [bindport] [forwardhost] [forwardport]				| 						| HERE 		|
| runas					| runas [domain\user] [pass] [command] [args]					| Windows API 			| HERE 		|
| runu 					| runu [pid] [command] [args]									|						| HERE 		|
| screenshot 			| screenshot [pid] <x68\|x64> [run time in seconds]			| Process Injection 	| HERE 		|
| setenv				| setenv [key] [value]											| 						| HERE 		|
| shell 				| shell [command] [args]										| cmd.exe 				| HERE 		|
| shinject				| `shinject [pid] <x86\|x64> [/path/to/file.bin]`				| Process Injection 	| HERE 		|