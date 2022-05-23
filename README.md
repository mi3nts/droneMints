# droneMints
##

- Boat (Otter) On Board Computer: 192.168.1.2
- Boat (Otter) Payload PC             : 192.168.1.3
- Boat (Otter) Biosonics MX          : 192.168.1.201
- Boat (Otter) Camera                   : 192.168.1.5
- Show Side (Trailer) Radio          : 192.168.1.10
- Boat (Otter) Radio                      : 192.168.1.20
- Arial Vehicle Radio (New Radio): 192.168.1.30 
- Walking Robot Radio                  : 192.168.1.40
- Boat (Otter) laptop/ VCS             : 192.168.1.58
- Arial Vehicle NUC                        : 192.168.1.200
- Robot Team Viz                           : 192.168.1.100
- Camera NUC                               : 192.168.1.24
- Boat (Otter) C1+                          : 192.168.1.220
- Arial Vehicle C1+                         : 192.168.1.221
- Walking Robot C1+                      : 192.168.1.222 
- Arial Vehicle Jetson                      : 192.168.1.223 
- Camera Front Under Water -: 192.168.1.180
- Camera Front Over Water  -: 192.168.1.181
- Camera Rear Under Water  -: 192.168.1.251
- Camera Rear Over Water   -: 192.168.1.252
- Camera Trailer Inside    -: 192.168.1.253
- Camera Trailer Outside   -: 192.168.1.254
- NAS Trailer   -: 192.168.1.240


Otter PC 1: otter@192.168.1.2  pswd: utd_0tter! (note the 0 instead of O)  
Otter PC 2: utd@192.168.1.3    pswd: utd_0tter! 

Over Water Camera PW: teamlary@

The TCP forwarding/serial port mapping should be as follows (COM0 = Serial 1):
 - COM0 (Airmar) on port 42001
 - COM1 (Manta 1) on port 42002
 - COM2 (Manta 2) on port 42003
 - COM3 (Manta 3) on port 42004
 - COM4 (LISST) on port 42005
 - MX on port 42006

## Data access for the air packges.
On any of the mfs accessible systems the data can be found @ `mfs/io/groups/lary/mints-imd/raw/sensorID`  The sensor IDs are listed below.
- Otter: 001e0610c2ed
- AltaX: 001e0610c1fb
- Vision60: 001e0610c42e


