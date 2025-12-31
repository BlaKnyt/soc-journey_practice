## Internal Traffic Review

##Time Stamp
31 December 2025
02:12:44

## Source IP
-192.168.8.50
  Device is an internal device on a private network because of the address block

## Destination IP
-192.168.8.186
  Device is an internal device on a private network because of the address block

## Port and Protocol
  Protocol: TCP
  Port: 445 - Server Message Block (SMB) Communication
  
## Analysis
The traffic is internal which may indicate file sharing or lateral movement between
devices. Port 445 was used meaning that it is open. This could open up the network
to various Denial of Service (DoS) attacks. The activity time stamp makes it more suspicious.

## Verdict and Recommendations
The activity needs to be monitored more to make sure that the traffic is safe. The devices
the port needs to be monitored as well to make sure that no external devices are using
the port as well.
