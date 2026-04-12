# How to make your IT Company more secure, if you are using a Workstation

In case, you need to dynamically give more accesses privileges to users who belong to a specific workstation, you need previously to do, the following actions.

+ Identify and list Users from Workstation. Any other Users are not allowed.
+ Identify and list all al CPU Model, Hardware Model, and Software plus the Company which commercialized such Software. Any other CPU Model, Hardware Model, and Software are not allowed.
+ Create Net Rules applied to the server, you are working on (Ubuntu, Windows Server, MacOS). These rules may stop any connection which do not belong to the Workstation.

For example: 

+ You can use a Rule that stops any Foreign Connection which does not belong to original server. Comparing IP Address Foreign vs IP Address Server (Company's Server).
+ Or indeed, you can create a Rule that stops any Server Connection which is trying to connect to an IP Address Foreign or Foreign Connection that is not inside the Workstation.


