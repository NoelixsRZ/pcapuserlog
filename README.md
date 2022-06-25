# pcapuserlog

Microsoft Windows [Versión 10.0.15063]
(c) 2017 Microsoft Corporation. Todos los derechos reservados.

C:\Users\Isacc>curl
"curl" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

C:\Users\Isacc>type
La sintaxis del comando no es correcta.

C:\Users\Isacc>cd C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin

C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin>dir
 El volumen de la unidad C es win10
 El número de serie del volumen es: 943F-498A

 Directorio de C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin

24/jun./2022  08:41 p. m.    <DIR>          .
24/jun./2022  08:41 p. m.    <DIR>          ..
26/abr./2022  03:12 a. m.           215,352 curl-ca-bundle.crt
11/may./2022  06:22 a. m.         5,818,952 curl.exe
11/may./2022  06:22 a. m.             2,206 libcurl-x64.def
11/may./2022  06:22 a. m.         5,620,808 libcurl-x64.dll
               4 archivos     11,657,318 bytes
               2 dirs  121,493,622,784 bytes libres

C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin>dir
 El volumen de la unidad C es win10
 El número de serie del volumen es: 943F-498A

 Directorio de C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin

24/jun./2022  08:41 p. m.    <DIR>          .
24/jun./2022  08:41 p. m.    <DIR>          ..
26/abr./2022  03:12 a. m.           215,352 curl-ca-bundle.crt
11/may./2022  06:22 a. m.         5,818,952 curl.exe
11/may./2022  06:22 a. m.             2,206 libcurl-x64.def
11/may./2022  06:22 a. m.         5,620,808 libcurl-x64.dll
               4 archivos     11,657,318 bytes
               2 dirs  121,443,454,976 bytes libres

C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin>curl
curl: try 'curl --help' or 'curl --manual' for more information

C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin>curl --help
Usage: curl [options...] <url>
 -d, --data <data>          HTTP POST data
 -f, --fail                 Fail fast with no output on HTTP errors
 -h, --help <category>      Get help for commands
 -i, --include              Include protocol response headers in the output
 -o, --output <file>        Write to file instead of stdout
 -O, --remote-name          Write output to a file named as the remote file
 -s, --silent               Silent mode
 -T, --upload-file <file>   Transfer local FILE to destination
 -u, --user <user:password> Server user and password
 -A, --user-agent <name>    Send User-Agent <name> to server
 -v, --verbose              Make the operation more talkative
 -V, --version              Show version number and quit

This is not the full help, this menu is stripped into categories.
Use "--help category" to get an overview of all categories.
For all options use the manual or "--help all".

C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin>curl
curl: try 'curl --help' or 'curl --manual' for more information

C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin>dir
 El volumen de la unidad C es win10
 El número de serie del volumen es: 943F-498A

 Directorio de C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin

24/jun./2022  08:41 p. m.    <DIR>          .
24/jun./2022  08:41 p. m.    <DIR>          ..
26/abr./2022  03:12 a. m.           215,352 curl-ca-bundle.crt
11/may./2022  06:22 a. m.         5,818,952 curl.exe
11/may./2022  06:22 a. m.             2,206 libcurl-x64.def
11/may./2022  06:22 a. m.         5,620,808 libcurl-x64.dll
               4 archivos     11,657,318 bytes
               2 dirs  121,422,368,768 bytes libres

C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin>curl https://gist.githubusercontent.com/kevinzepeda/94bc137c3487125e3b1524a5816e3627/raw/fe01abc34d163bee0b05215f6f3ee0c57d799fee/user.log -o user.log
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  114k  100  114k    0     0  53775      0  0:00:02  0:00:02 --:--:-- 53860

C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin>dir
 El volumen de la unidad C es win10
 El número de serie del volumen es: 943F-498A

 Directorio de C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin

24/jun./2022  09:03 p. m.    <DIR>          .
24/jun./2022  09:03 p. m.    <DIR>          ..
26/abr./2022  03:12 a. m.           215,352 curl-ca-bundle.crt
11/may./2022  06:22 a. m.         5,818,952 curl.exe
11/may./2022  06:22 a. m.             2,206 libcurl-x64.def
11/may./2022  06:22 a. m.         5,620,808 libcurl-x64.dll
24/jun./2022  09:03 p. m.           117,039 user.log
               5 archivos     11,774,357 bytes
               2 dirs  121,420,713,984 bytes libres

C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin>type user.log
 01
root 08:51:01 INFO   :.main: *************** RSVP Agent started ***************
 02
root 08:51:01 INFO   :...locate_configFile: Specified configuration file: /u/user10/rsvpd1.conf
root 08:51:01 INFO   :.main: Using log level 511
root 08:51:01 INFO   :..settcpimage: Get TCP images rc - EDC8112I Operation not supported on socket.
 03
root 08:51:01 INFO   :..settcpimage: Associate with TCP/IP image name = TCPCS
root 08:51:02 INFO   :..reg_process: registering process with the system
root 08:51:02 INFO   :..reg_process: attempt OS/390 registration
root 08:51:02 INFO   :..reg_process: return from registration rc=0
 04
root 08:51:10 TRACE  :...read_physical_netif: Home list entries returned = 7
root 08:51:10 INFO   :...read_physical_netif: index #0, interface VLINK1 has address 129.1.1.1, ifidx 0
root 08:51:10 INFO   :...read_physical_netif: index #1, interface TR1 has address 9.37.65.139, ifidx 1
root 08:51:10 INFO   :...read_physical_netif: index #2, interface LINK11 has address 9.67.100.1, ifidx 2
root 08:51:10 INFO   :...read_physical_netif: index #3, interface LINK12 has address 9.67.101.1, ifidx 3
root 08:51:10 INFO   :...read_physical_netif: index #4, interface CTCD0 has address 9.67.116.98, ifidx 4
root 08:51:10 INFO   :...read_physical_netif: index #5, interface CTCD2 has address 9.67.117.98, ifidx 5
root 08:51:10 INFO   :...read_physical_netif: index #6, interface LOOPBACK has address 127.0.0.1, ifidx 0
root 08:51:10 INFO   :....mailslot_create: creating mailslot for timer
root 08:51:10 INFO   :...mailbox_register: mailbox allocated for timer
 05
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
 06
root 08:51:10 WARNING:.....mailslot_create: setsockopt(MCAST_ADD) failed - EDC8116I Address not available.
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 129.1.1.1, entity for rsvp allocated and initialized
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 WARNING:.....mailslot_create: setsockopt(MCAST_ADD) failed - EDC8116I Address not available.
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 9.37.65.139, entity for rsvp allocated and
initialized
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 WARNING:.....mailslot_create: setsockopt(MCAST_ADD) failed - EDC8116I Address not available.
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 9.67.100.1, entity for rsvp allocated and initialized
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 WARNING:.....mailslot_create: setsockopt(MCAST_ADD) failed - EDC8116I Address not available.
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 9.67.101.1, entity for rsvp allocated and initialized
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 9.67.116.98, entity for rsvp allocated and
initialized
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 9.67.117.98, entity for rsvp allocated and
root 08:51:03 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:034 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:043 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:04 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......dir has removed: creating mailslot for RSVP
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 127.0.0.1, entity for rsvp allocated and initialized
root 08:51:10 INFO   :......mailslot_create: creating socket for querying route
root 08:51:10 INFO   :.....mailbox_register: no mailbox necessary for forward
root 08:51:10 INFO   :......mailslot_create: creating mailslot for route engine - informational socket
root 08:51:10 TRACE  :......mailslot_create: ready to accept informational socket connection
root 08:51:11 INFO   :.....mailbox_register: mailbox allocated for route
root 08:51:11 INFO   :.....mailslot_create: creating socket for traffic control module
root 08:51:11 INFO   :....mailbox_register: no mailbox necessary for traffic-control
root 08:51:11 INFO   :....mailslot_create: creating mailslot for RSVP client API
root 08:51:11 INFO   :...mailbox_register: mailbox allocated for rsvp-api
root 08:51:11 INFO   :...mailslot_create: creating mailslot for terminate
root 08:51:11 INFO   :..mailbox_register: mailbox allocated for terminate
root 08:51:11 INFO   :...mailslot_create: creating mailslot for dump
root 08:51:11 INFO   :..mailbox_register: mailbox allocated for dump
root 08:51:11 INFO   :...mailslot_create: creating mailslot for (broken) pipe
root 08:51:11 INFO   :..mailbox_register: mailbox allocated for pipe
 07
root 08:51:11 INFO   :.main: rsvpd initialization complete
 08
root 08:52:50 INFO   :......rsvp_api_open: accepted a new connection for rapi
root 08:52:50 INFO   :.......mailbox_register: mailbox allocated for mailbox
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 does not exist
 09
root 08:52:50 EVENT  :.....api_reader: api request SESSION
 10
root 08:52:50 TRACE  :......rsvp_event_establishSession: local node will send
root 08:52:50 INFO   :........router_forward_getOI: Ioctl to get route entry successful
root 08:52:50 TRACE  :........router_forward_getOI:         source address:   9.67.116.98
root 08:52:50 TRACE  :........router_forward_getOI:         out inf:   9.67.116.98
root 08:52:50 TRACE  :........router_forward_getOI:         gateway:   0.0.0.0
root 08:52:50 TRACE  :........router_forward_getOI:         route handle:   7f5251c8
 11
root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22

root 08:52:50 INFO   :.......init_policyAPI: ReadBuffer:  Entering

root 08:52:51 INFO   :.......init_policyAPI: ReadBuffer:  Exiting

root 08:52:51 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Exiting
root 08:52:51 INFO   :.......init_policyAPI: Policy API initialized
root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindActionName:  Entering

root 08:52:51 INFO   :......rpapi_getPolicyData: ReadBuffer:  Entering

root 08:52:51 INFO   :......rpapi_getPolicyData: ReadBuffer:  Exiting

root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindActionName:  Result = 0

root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindActionName:  Exiting

 14
root 08:52:51 INFO   :......rpapi_getPolicyData: found action name CLCat2 for
flow[sess=9.67.116.99:1047:6,source=9.67.116.98:8000]
root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindServiceDetailsOnActName:  Entering

root 08:52:51 INFO   :......rpapi_getPolicyData: ReadBuffer:  Entering

root 08:52:51 INFO   :......rpapi_getPolicyData: ReadBuffer:  Exiting

root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindServiceDetailsOnActName:  Result = 0

root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindServiceDetailsOnActName:  Exiting

root 08:52:51 INFO   :.....api_reader: appl chose service type 1
root 08:52:51 INFO   :......rpapi_getSpecData: RSVPGetTSpec:  Entering

root 08:52:51 INFO   :......rpapi_getSpecData: RSVPGetTSpec:  Result = 0

root 08:52:51 INFO   :......rpapi_getSpecData: RSVPGetTSpec:  Exiting

root 08:52:51 TRACE  :.....api_reader: new service=1, old service=0
root 08:52:51 INFO   :.......rsvp_flow_stateMachine: state SESSIONED, event PATHDELTA
 15
root 08:52:51 TRACE  :........rsvp_action_nHop: constructing a PATH
root 08:52:51 TRACE  :........flow_timer_start: started T1
 16
root 08:52:51 TRACE  :.......rsvp_flow_stateMachine: entering state PATHED
root 08:52:51 TRACE  :........mailslot_send: sending to (9.67.116.99:0)
root 08:52:51 TRACE  :........mailslot_send: sending to (9.67.116.99:1698)
 17
root 08:52:51 TRACE  :.....rsvp_event: received event from RAW-IP on interface 9.67.116.98
root 08:52:51 TRACE  :......rsvp_explode_packet: v=1,flg=0,type=2,cksm=54875,ttl=255,rsv=0,len=84
root 08:52:51 TRACE  :.......rsvp_parse_objects: STYLE is WF
root 08:52:51 INFO   :.......rsvp_parse_objects: obj RSVP_HOP hop=9.67.116.99, lih=0
root 08:52:51 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
root 08:52:51 INFO   :.......rsvp_flow_stateMachine: state PATHED, event RESVDELTA
 18
root 08:52:51 TRACE  :........traffic_action_oif: is to install filter
root 08:52:51 INFO   :.........qosmgr_request: src-9.67.116.98:8000 dst-9.67.116.99:1047 proto-6
rthdl-7f5251c8
 19
root 08:52:51 INFO   :.........qosmgr_request: [CL r=90000 b=6000 p=110000 m=1024 M=2048]
root 08:52:51 INFO   :.........qosmgr_request: Ioctl to add reservation successful
root 08:52:51 INFO   :..........rpapi_Reg_UnregFlow: RSVPPutActionName:  Entering
root 08:52:51 INFO   :..........rpapi_Reg_UnregFlow: ReadBuffer:  Entering

root 08:52:52 INFO   :..........rpapi_Reg_UnregFlow: ReadBuffer:  Exiting

root 08:52:52 INFO   :..........rpapi_Reg_UnregFlow: RSVPPutActionName:  Result = 0

root 08:52:52 INFO   :..........rpapi_Reg_UnregFlow: RSVPPutActionName:  Exiting

root 08:52:52 INFO   :..........rpapi_Reg_UnregFlow: flow[sess=9.67.116.99:1047:6,
source=9.67.116.98:8000] registered with CLCat2
root 08:52:52 EVENT  :..........qosmgr_response: RESVRESP from qosmgr, reason=0, qoshandle=8b671d0
root 08:52:52 INFO   :..........qosmgr_response: src-9.67.116.98:8000 dst-9.67.116.99:1047 proto-6
root 08:52:52 TRACE  :...........traffic_reader: tc response msg=1, status=1
root 08:52:52 INFO   :...........traffic_reader: Reservation req successful[session=9.67.116.99:1047:6,
source=9.67.116.98:8000, qoshd=8b671d0]
 20
root 08:52:52 TRACE  :........api_action_sender: constructing a RESV
root 08:52:52 TRACE  :........flow_timer_stop: stopped T1
root 08:52:52 TRACE  :........flow_timer_stop: Stop T4
root 08:52:52 TRACE  :........flow_timer_start: started T1
root 08:52:52 TRACE  :........flow_timer_start: Start T4
 21
root 08:52:52 TRACE  :.......rsvp_flow_stateMachine: entering state RESVED
 22
root 08:53:07 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:07 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:07 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:07 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:07 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:07 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:07 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:07 TRACE  :.......flow_timer_start: started T1
root 08:53:07 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:07 TRACE  :.......mailslot_send: sending to (9.67.116.99:0) 20
root 08:52:52 TRACE  :........api_action_sender: constructing a RESV
root 08:52:52 TRACE  :........flow_timer_stop: stopped T1
root 08:52:52 TRACE  :........flow_timer_stop: Stop T4
root 08:52:52 TRACE  :........flow_timer_start: started T1
root 08:52:52 TRACE  :........flow_timer_start: Start T4
 21
root 08:52:52 TRACE  :.......rsvp_flow_stateMachine: entering state RESVED
 22
root 08:53:07 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:07 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:07 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:07 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:07 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:07 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:07 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:07 TRACE  :.......flow_timer_start: started T1
root 08:53:07 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:07 TRACE  :.......mailslot_send: sending to (9.67.116.99:0) 20
root 08:52:52 TRACE  :........api_action_sender: constructing a RESV
root 08:52:52 TRACE  :........flow_timer_stop: stopped T1
root 08:52:52 TRACE  :........flow_timer_stop: Stop T4
root 08:52:52 TRACE  :........flow_timer_start: started T1
root 08:52:52 TRACE  :........flow_timer_start: Start T4
 21
root 08:52:52 TRACE  :.......rsvp_flow_stateMachine: entering state RESVED
 22
root 08:53:07 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:07 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:07 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:07 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:07 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:07 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:07 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:07 TRACE  :.......flow_timer_start: started T1
root 08:53:07 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:07 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
 23
root 08:53:22 TRACE  :.....rsvp_event: received event from RAW-IP on interface 9.67.116.98
root 08:53:22 TRACE  :......rsvp_explode_packet: v=1,flg=0,type=2,cksm=54875,ttl=255,rsv=0,len=84
root 08:53:22 TRACE  :.......rsvp_parse_objects: STYLE is WF
root 08:53:22 INFO   :.......rsvp_parse_objects: obj RSVP_HOP hop=9.67.116.99, lih=0
root 08:53:22 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
root 08:53:22 INFO   :.......rsvp_flow_stateMachine: state RESVED, event RESV
root 08:53:22 TRACE  :........flow_timer_stop: Stop T4
root 08:53:22 TRACE  :........flow_timer_start: Start T4
root 08:53:22 TRACE  :.......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:22 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:22 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:22 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:22 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:22 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:22 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:22 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:22 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:22 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:22 TRACE  :.......flow_timer_start: started T1
root 08:53:22 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:22 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:53:38 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:38 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:38 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:38 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:38 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:38 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:38 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:38 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:38 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:38 TRACE  :.......flow_timer_start: started T1
root 08:53:38 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:38 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:53:52 TRACE  :.....rsvp_event: received event from RAW-IP on interface 9.67.116.98
root 08:53:52 TRACE  :......rsvp_explode_packet: v=1,flg=0,type=2,cksm=54875,ttl=255,rsv=0,len=84
root 08:53:52 TRACE  :.......rsvp_parse_objects: STYLE is WF
root 08:53:52 INFO   :.......rsvp_parse_objects: obj RSVP_HOP hop=9.67.116.99, lih=0
root 08:53:52 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
root 08:53:52 INFO   :.......rsvp_flow_stateMachine: state RESVED, event RESV
root 08:53:52 TRACE  :........flow_timer_stop: Stop T4
root 08:53:52 TRACE  :........flow_timer_start: Start T4
root 08:53:52 TRACE  :.......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:53 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:53 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:53 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:53 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:53 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:53 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:53 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:53 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:53 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:53 TRACE  :.......flow_timer_start: started T1
root 08:53:53 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:53 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:54:09 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:54:09 TRACE  :.....event_timerT1_expire: T1 expired
root 08:54:09 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:54:09 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:54:09 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:54:09 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:54:09 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:54:09 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:54:09 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:54:09 TRACE  :.......flow_timer_start: started T1
root 08:54:09 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:54:09 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:54:22 TRACE  :.....rsvp_event: received event from RAW-IP on interface 9.67.116.98
root 08:54:22 TRACE  :......rsvp_explode_packet: v=1,flg=0,type=2,cksm=54875,ttl=255,rsv=0,len=84
root 08:54:22 TRACE  :.......rsvp_parse_objects: STYLE is WF
root 08:54:22 INFO   :.......rsvp_parse_objects: obj RSVP_HOP hop=9.67.116.99, lih=0
root 08:54:22 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
root 08:54:22 INFO   :.......rsvp_flow_stateMachine: state RESVED, event RESV
root 08:54:22 TRACE  :........flow_timer_stop: Stop T4
root 08:54:22 TRACE  :........flow_timer_start: Start T4
root 08:54:22 TRACE  :.......rsvp_flow_stateMachine: reentering state RESVED
root 08:54:24 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:54:24 TRACE  :.....event_timerT1_expire: T1 expired
root 08:54:24 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:54:24 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:54:24 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:54:24 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:54:24 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:54:24 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:54:24 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:54:24 TRACE  :.......flow_timer_start: started T1
root 08:54:24 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:54:24 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:54:35 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 24
root 08:54:35 EVENT  :.....api_reader: api request SENDER_WITHDRAW
root 08:54:35 INFO   :.......rsvp_flow_stateMachine: state RESVED, event PATHTEAR
 25
root 08:54:35 TRACE  :........traffic_action_oif: is to remove filter 20
root 08:52:52 TRACE  :........api_action_sender: constructing a RESV
root 08:52:52 TRACE  :........flow_timer_stop: stopped T1
root 08:52:52 TRACE  :........flow_timer_stop: Stop T4
root 08:52:52 TRACE  :........flow_timer_start: started T1
root 08:52:52 TRACE  :........flow_timer_start: Start T4
 21
root 08:52:52 TRACE  :.......rsvp_flow_stateMachine: entering state RESVED
 22
root 08:53:07 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:07 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:07 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:07 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:07 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:07 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:07 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:07 TRACE  :.......flow_timer_start: started T1
root 08:53:07 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:07 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:54:35 INFO   :.........qosmgr_request: Ioctl to remove reservation successful
root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: RSVPRemActionName:  Entering

root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: ReadBuffer:  Entering

root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: ReadBuffer:  Exiting

root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: RSVPRemActionName:  Result = 0

root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: RSVPRemActionName:  Exiting

root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: flow[sess=9.67.116.99:1047:6,
source=9.67.116.98:8000] unregistered from CLCat2
root 08:54:35 EVENT  :..........qosmgr_response: DELRESP from qosmgr, reason=0, qoshandle=0
root 08:54:35 INFO   :..........qosmgr_response: src-9.67.116.98:8000 dst-9.67.116.99:1047 proto-6
root 08:54:35 TRACE  :...........traffic_reader: tc response msg=3, status=1
 26
root 08:54:35 TRACE  :........rsvp_action_nHop: constructing a PATHTEAR
root 08:54:35 TRACE  :........flow_timer_stop: stopped T1
root 08:54:35 TRACE  :........flow_timer_stop: Stop T4
 27
root 08:54:35 TRACE  :.......rsvp_flow_stateMachine: entering state SESSIONED
root 08:54:35 TRACE  :........mailslot_send: sending to (9.67.116.99:0)
root 08:54:35 TRACE  :......rsvp_event_propagate: flow[session=9.67.116.99:1047:6,
source=9.67.116.98:8000] ceased
 28
root 08:54:35 EVENT  :.....api_reader: api request CLOSE
root 08:54:35 INFO   :.......rsvp_flow_stateMachine: state SESSIONED, event PATHTEAR
root 08:54:35 PROTERR:.......rsvp_flow_stateMachine: state SESSIONED does not expect event PATHTEAR
 29
root 08:54:53 EVENT  :..mailslot_sitter: process received signal SIGTERM
root 08:54:53 INFO   :...check_signals: received TERM signal
root 08:54:53 INFO   :......term_policyAPI: UnRegisterFromPolicyAPI:  Entering

root 08:54:53 INFO   :......term_policyAPI: ReadBuffer:  Entering

root 08:54:53 INFO   :......term_policyAPI: ReadBuffer:  Exiting

root 08:54:53 INFO   :......term_policyAPI: UnRegisterFromPolicyAPI:  Result = 0

root 08:54:53 INFO   :......term_policyAPI: UnRegisterFromPolicyAPI:  Exiting

root 08:54:53 INFO   :......term_policyAPI: APITerminate:  Entering

root 08:54:53 INFO   :......term_policyAPI: APITerminate:  Exiting

root 08:54:53 INFO   :......term_policyAPI: Policy API terminated
root 08:54:53 INFO   :......dreg_process: deregistering process with the system
root 08:54:53 INFO   :......dreg_process: attempt to dereg (ifaeddrg_byaddr)
root 08:54:53 INFO   :......dreg_process: rc from ifaeddrg_byaddr  rc =0
root 08:54:53 INFO   :.....terminator: process terminated with exit code 0
C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin>type user.log
 01
root 08:51:01 INFO   :.main: *************** RSVP Agent started ***************
 02
root 08:51:01 INFO   :...locate_configFile: Specified configuration file: /u/user10/rsvpd1.conf
root 08:51:01 INFO   :.main: Using log level 511
root 08:51:01 INFO   :..settcpimage: Get TCP images rc - EDC8112I Operation not supported on socket.
 03
root 08:51:01 INFO   :..settcpimage: Associate with TCP/IP image name = TCPCS
root 08:51:02 INFO   :..reg_process: registering process with the system
root 08:51:02 INFO   :..reg_process: attempt OS/390 registration
root 08:51:02 INFO   :..reg_process: return from registration rc=0
 04
root 08:51:10 TRACE  :...read_physical_netif: Home list entries returned = 7
root 08:51:10 INFO   :...read_physical_netif: index #0, interface VLINK1 has address 129.1.1.1, ifidx 0
root 08:51:10 INFO   :...read_physical_netif: index #1, interface TR1 has address 9.37.65.139, ifidx 1
root 08:51:10 INFO   :...read_physical_netif: index #2, interface LINK11 has address 9.67.100.1, ifidx 2
root 08:51:10 INFO   :...read_physical_netif: index #3, interface LINK12 has address 9.67.101.1, ifidx 3
root 08:51:10 INFO   :...read_physical_netif: index #4, interface CTCD0 has address 9.67.116.98, ifidx 4
root 08:51:10 INFO   :...read_physical_netif: index #5, interface CTCD2 has address 9.67.117.98, ifidx 5
root 08:51:10 INFO   :...read_physical_netif: index #6, interface LOOPBACK has address 127.0.0.1, ifidx 0
root 08:51:10 INFO   :....mailslot_create: creating mailslot for timer
root 08:51:10 INFO   :...mailbox_register: mailbox allocated for timer
 05
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
 06
root 08:51:10 WARNING:.....mailslot_create: setsockopt(MCAST_ADD) failed - EDC8116I Address not available.
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 129.1.1.1, entity for rsvp allocated and initialized
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 WARNING:.....mailslot_create: setsockopt(MCAST_ADD) failed - EDC8116I Address not available.
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 9.37.65.139, entity for rsvp allocated and
initialized
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 WARNING:.....mailslot_create: setsockopt(MCAST_ADD) failed - EDC8116I Address not available.
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 9.67.100.1, entity for rsvp allocated and initialized
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 WARNING:.....mailslot_create: setsockopt(MCAST_ADD) failed - EDC8116I Address not available.
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 9.67.101.1, entity for rsvp allocated and initialized
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 9.67.116.98, entity for rsvp allocated and
initialized
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 9.67.117.98, entity for rsvp allocated and
root 08:51:03 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:034 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:043 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:04 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......dir has removed: creating mailslot for RSVP
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 127.0.0.1, entity for rsvp allocated and initialized
root 08:51:10 INFO   :......mailslot_create: creating socket for querying route
root 08:51:10 INFO   :.....mailbox_register: no mailbox necessary for forward
root 08:51:10 INFO   :......mailslot_create: creating mailslot for route engine - informational socket
root 08:51:10 TRACE  :......mailslot_create: ready to accept informational socket connection
root 08:51:11 INFO   :.....mailbox_register: mailbox allocated for route
root 08:51:11 INFO   :.....mailslot_create: creating socket for traffic control module
root 08:51:11 INFO   :....mailbox_register: no mailbox necessary for traffic-control
root 08:51:11 INFO   :....mailslot_create: creating mailslot for RSVP client API
root 08:51:11 INFO   :...mailbox_register: mailbox allocated for rsvp-api
root 08:51:11 INFO   :...mailslot_create: creating mailslot for terminate
root 08:51:11 INFO   :..mailbox_register: mailbox allocated for terminate
root 08:51:11 INFO   :...mailslot_create: creating mailslot for dump
root 08:51:11 INFO   :..mailbox_register: mailbox allocated for dump
root 08:51:11 INFO   :...mailslot_create: creating mailslot for (broken) pipe
root 08:51:11 INFO   :..mailbox_register: mailbox allocated for pipe
 07
root 08:51:11 INFO   :.main: rsvpd initialization complete
 08
root 08:52:50 INFO   :......rsvp_api_open: accepted a new connection for rapi
root 08:52:50 INFO   :.......mailbox_register: mailbox allocated for mailbox
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 does not exist
 09
root 08:52:50 EVENT  :.....api_reader: api request SESSION
 10
root 08:52:50 TRACE  :......rsvp_event_establishSession: local node will send
root 08:52:50 INFO   :........router_forward_getOI: Ioctl to get route entry successful
root 08:52:50 TRACE  :........router_forward_getOI:         source address:   9.67.116.98
root 08:52:50 TRACE  :........router_forward_getOI:         out inf:   9.67.116.98
root 08:52:50 TRACE  :........router_forward_getOI:         gateway:   0.0.0.0
root 08:52:50 TRACE  :........router_forward_getOI:         route handle:   7f5251c8
 11
root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22

root 08:52:50 INFO   :.......init_policyAPI: ReadBuffer:  Entering

root 08:52:51 INFO   :.......init_policyAPI: ReadBuffer:  Exiting

root 08:52:51 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Exiting
root 08:52:51 INFO   :.......init_policyAPI: Policy API initialized
root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindActionName:  Entering

root 08:52:51 INFO   :......rpapi_getPolicyData: ReadBuffer:  Entering

root 08:52:51 INFO   :......rpapi_getPolicyData: ReadBuffer:  Exiting

root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindActionName:  Result = 0

root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindActionName:  Exiting

 14
root 08:52:51 INFO   :......rpapi_getPolicyData: found action name CLCat2 for
flow[sess=9.67.116.99:1047:6,source=9.67.116.98:8000]
root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindServiceDetailsOnActName:  Entering

root 08:52:51 INFO   :......rpapi_getPolicyData: ReadBuffer:  Entering

root 08:52:51 INFO   :......rpapi_getPolicyData: ReadBuffer:  Exiting

root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindServiceDetailsOnActName:  Result = 0

root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindServiceDetailsOnActName:  Exiting

root 08:52:51 INFO   :.....api_reader: appl chose service type 1
root 08:52:51 INFO   :......rpapi_getSpecData: RSVPGetTSpec:  Entering

root 08:52:51 INFO   :......rpapi_getSpecData: RSVPGetTSpec:  Result = 0

root 08:52:51 INFO   :......rpapi_getSpecData: RSVPGetTSpec:  Exiting

root 08:52:51 TRACE  :.....api_reader: new service=1, old service=0
root 08:52:51 INFO   :.......rsvp_flow_stateMachine: state SESSIONED, event PATHDELTA
 15
root 08:52:51 TRACE  :........rsvp_action_nHop: constructing a PATH
root 08:52:51 TRACE  :........flow_timer_start: started T1
 16
root 08:52:51 TRACE  :.......rsvp_flow_stateMachine: entering state PATHED
root 08:52:51 TRACE  :........mailslot_send: sending to (9.67.116.99:0)
root 08:52:51 TRACE  :........mailslot_send: sending to (9.67.116.99:1698)
 17
root 08:52:51 TRACE  :.....rsvp_event: received event from RAW-IP on interface 9.67.116.98
root 08:52:51 TRACE  :......rsvp_explode_packet: v=1,flg=0,type=2,cksm=54875,ttl=255,rsv=0,len=84
root 08:52:51 TRACE  :.......rsvp_parse_objects: STYLE is WF
root 08:52:51 INFO   :.......rsvp_parse_objects: obj RSVP_HOP hop=9.67.116.99, lih=0
root 08:52:51 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
root 08:52:51 INFO   :.......rsvp_flow_stateMachine: state PATHED, event RESVDELTA
 18
root 08:52:51 TRACE  :........traffic_action_oif: is to install filter
root 08:52:51 INFO   :.........qosmgr_request: src-9.67.116.98:8000 dst-9.67.116.99:1047 proto-6
rthdl-7f5251c8
 19
root 08:52:51 INFO   :.........qosmgr_request: [CL r=90000 b=6000 p=110000 m=1024 M=2048]
root 08:52:51 INFO   :.........qosmgr_request: Ioctl to add reservation successful
root 08:52:51 INFO   :..........rpapi_Reg_UnregFlow: RSVPPutActionName:  Entering
root 08:52:51 INFO   :..........rpapi_Reg_UnregFlow: ReadBuffer:  Entering

root 08:52:52 INFO   :..........rpapi_Reg_UnregFlow: ReadBuffer:  Exiting

root 08:52:52 INFO   :..........rpapi_Reg_UnregFlow: RSVPPutActionName:  Result = 0

root 08:52:52 INFO   :..........rpapi_Reg_UnregFlow: RSVPPutActionName:  Exiting

root 08:52:52 INFO   :..........rpapi_Reg_UnregFlow: flow[sess=9.67.116.99:1047:6,
source=9.67.116.98:8000] registered with CLCat2
root 08:52:52 EVENT  :..........qosmgr_response: RESVRESP from qosmgr, reason=0, qoshandle=8b671d0
root 08:52:52 INFO   :..........qosmgr_response: src-9.67.116.98:8000 dst-9.67.116.99:1047 proto-6
root 08:52:52 TRACE  :...........traffic_reader: tc response msg=1, status=1
root 08:52:52 INFO   :...........traffic_reader: Reservation req successful[session=9.67.116.99:1047:6,
source=9.67.116.98:8000, qoshd=8b671d0]
 20
root 08:52:52 TRACE  :........api_action_sender: constructing a RESV
root 08:52:52 TRACE  :........flow_timer_stop: stopped T1
root 08:52:52 TRACE  :........flow_timer_stop: Stop T4
root 08:52:52 TRACE  :........flow_timer_start: started T1
root 08:52:52 TRACE  :........flow_timer_start: Start T4
 21
root 08:52:52 TRACE  :.......rsvp_flow_stateMachine: entering state RESVED
 22
root 08:53:07 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:07 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:07 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:07 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:07 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:07 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:07 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:07 TRACE  :.......flow_timer_start: started T1
root 08:53:07 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:07 TRACE  :.......mailslot_send: sending to (9.67.116.99:0) 20
root 08:52:52 TRACE  :........api_action_sender: constructing a RESV
root 08:52:52 TRACE  :........flow_timer_stop: stopped T1
root 08:52:52 TRACE  :........flow_timer_stop: Stop T4
root 08:52:52 TRACE  :........flow_timer_start: started T1
root 08:52:52 TRACE  :........flow_timer_start: Start T4
 21
root 08:52:52 TRACE  :.......rsvp_flow_stateMachine: entering state RESVED
 22
root 08:53:07 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:07 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:07 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:07 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:07 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:07 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:07 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:07 TRACE  :.......flow_timer_start: started T1
root 08:53:07 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:07 TRACE  :.......mailslot_send: sending to (9.67.116.99:0) 20
root 08:52:52 TRACE  :........api_action_sender: constructing a RESV
root 08:52:52 TRACE  :........flow_timer_stop: stopped T1
root 08:52:52 TRACE  :........flow_timer_stop: Stop T4
root 08:52:52 TRACE  :........flow_timer_start: started T1
root 08:52:52 TRACE  :........flow_timer_start: Start T4
 21
root 08:52:52 TRACE  :.......rsvp_flow_stateMachine: entering state RESVED
 22
root 08:53:07 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:07 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:07 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:07 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:07 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:07 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:07 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:07 TRACE  :.......flow_timer_start: started T1
root 08:53:07 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:07 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
 23
root 08:53:22 TRACE  :.....rsvp_event: received event from RAW-IP on interface 9.67.116.98
root 08:53:22 TRACE  :......rsvp_explode_packet: v=1,flg=0,type=2,cksm=54875,ttl=255,rsv=0,len=84
root 08:53:22 TRACE  :.......rsvp_parse_objects: STYLE is WF
root 08:53:22 INFO   :.......rsvp_parse_objects: obj RSVP_HOP hop=9.67.116.99, lih=0
root 08:53:22 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
root 08:53:22 INFO   :.......rsvp_flow_stateMachine: state RESVED, event RESV
root 08:53:22 TRACE  :........flow_timer_stop: Stop T4
root 08:53:22 TRACE  :........flow_timer_start: Start T4
root 08:53:22 TRACE  :.......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:22 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:22 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:22 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:22 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:22 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:22 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:22 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:22 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:22 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:22 TRACE  :.......flow_timer_start: started T1
root 08:53:22 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:22 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:53:38 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:38 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:38 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:38 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:38 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:38 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:38 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:38 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:38 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:38 TRACE  :.......flow_timer_start: started T1
root 08:53:38 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:38 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:53:52 TRACE  :.....rsvp_event: received event from RAW-IP on interface 9.67.116.98
root 08:53:52 TRACE  :......rsvp_explode_packet: v=1,flg=0,type=2,cksm=54875,ttl=255,rsv=0,len=84
root 08:53:52 TRACE  :.......rsvp_parse_objects: STYLE is WF
root 08:53:52 INFO   :.......rsvp_parse_objects: obj RSVP_HOP hop=9.67.116.99, lih=0
root 08:53:52 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
root 08:53:52 INFO   :.......rsvp_flow_stateMachine: state RESVED, event RESV
root 08:53:52 TRACE  :........flow_timer_stop: Stop T4
root 08:53:52 TRACE  :........flow_timer_start: Start T4
root 08:53:52 TRACE  :.......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:53 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:53 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:53 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:53 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:53 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:53 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:53 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:53 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:53 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:53 TRACE  :.......flow_timer_start: started T1
root 08:53:53 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:53 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:54:09 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:54:09 TRACE  :.....event_timerT1_expire: T1 expired
root 08:54:09 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:54:09 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:54:09 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:54:09 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:54:09 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:54:09 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:54:09 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:54:09 TRACE  :.......flow_timer_start: started T1
root 08:54:09 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:54:09 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:54:22 TRACE  :.....rsvp_event: received event from RAW-IP on interface 9.67.116.98
root 08:54:22 TRACE  :......rsvp_explode_packet: v=1,flg=0,type=2,cksm=54875,ttl=255,rsv=0,len=84
root 08:54:22 TRACE  :.......rsvp_parse_objects: STYLE is WF
root 08:54:22 INFO   :.......rsvp_parse_objects: obj RSVP_HOP hop=9.67.116.99, lih=0
root 08:54:22 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
root 08:54:22 INFO   :.......rsvp_flow_stateMachine: state RESVED, event RESV
root 08:54:22 TRACE  :........flow_timer_stop: Stop T4
root 08:54:22 TRACE  :........flow_timer_start: Start T4
root 08:54:22 TRACE  :.......rsvp_flow_stateMachine: reentering state RESVED
root 08:54:24 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:54:24 TRACE  :.....event_timerT1_expire: T1 expired
root 08:54:24 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:54:24 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:54:24 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:54:24 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:54:24 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:54:24 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:54:24 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:54:24 TRACE  :.......flow_timer_start: started T1
root 08:54:24 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:54:24 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:54:35 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 24
root 08:54:35 EVENT  :.....api_reader: api request SENDER_WITHDRAW
root 08:54:35 INFO   :.......rsvp_flow_stateMachine: state RESVED, event PATHTEAR
 25
root 08:54:35 TRACE  :........traffic_action_oif: is to remove filter 20
root 08:52:52 TRACE  :........api_action_sender: constructing a RESV
root 08:52:52 TRACE  :........flow_timer_stop: stopped T1
root 08:52:52 TRACE  :........flow_timer_stop: Stop T4
root 08:52:52 TRACE  :........flow_timer_start: started T1
root 08:52:52 TRACE  :........flow_timer_start: Start T4
 21
root 08:52:52 TRACE  :.......rsvp_flow_stateMachine: entering state RESVED
 22
root 08:53:07 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:07 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:07 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:07 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:07 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:07 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:07 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:07 TRACE  :.......flow_timer_start: started T1
root 08:53:07 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:07 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:54:35 INFO   :.........qosmgr_request: Ioctl to remove reservation successful
root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: RSVPRemActionName:  Entering

root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: ReadBuffer:  Entering

root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: ReadBuffer:  Exiting

root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: RSVPRemActionName:  Result = 0

root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: RSVPRemActionName:  Exiting

root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: flow[sess=9.67.116.99:1047:6,
source=9.67.116.98:8000] unregistered from CLCat2
root 08:54:35 EVENT  :..........qosmgr_response: DELRESP from qosmgr, reason=0, qoshandle=0
root 08:54:35 INFO   :..........qosmgr_response: src-9.67.116.98:8000 dst-9.67.116.99:1047 proto-6
root 08:54:35 TRACE  :...........traffic_reader: tc response msg=3, status=1
 26
root 08:54:35 TRACE  :........rsvp_action_nHop: constructing a PATHTEAR
root 08:54:35 TRACE  :........flow_timer_stop: stopped T1
root 08:54:35 TRACE  :........flow_timer_stop: Stop T4
 27
root 08:54:35 TRACE  :.......rsvp_flow_stateMachine: entering state SESSIONED
root 08:54:35 TRACE  :........mailslot_send: sending to (9.67.116.99:0)
root 08:54:35 TRACE  :......rsvp_event_propagate: flow[session=9.67.116.99:1047:6,
source=9.67.116.98:8000] ceased
 28
root 08:54:35 EVENT  :.....api_reader: api request CLOSE
root 08:54:35 INFO   :.......rsvp_flow_stateMachine: state SESSIONED, event PATHTEAR
root 08:54:35 PROTERR:.......rsvp_flow_stateMachine: state SESSIONED does not expect event PATHTEAR
 29
root 08:54:53 EVENT  :..mailslot_sitter: process received signal SIGTERM
root 08:54:53 INFO   :...check_signals: received TERM signal
root 08:54:53 INFO   :......term_policyAPI: UnRegisterFromPolicyAPI:  Entering

root 08:54:53 INFO   :......term_policyAPI: ReadBuffer:  Entering

root 08:54:53 INFO   :......term_policyAPI: ReadBuffer:  Exiting

root 08:54:53 INFO   :......term_policyAPI: UnRegisterFromPolicyAPI:  Result = 0

root 08:54:53 INFO   :......term_policyAPI: UnRegisterFromPolicyAPI:  Exiting

root 08:54:53 INFO   :......term_policyAPI: APITerminate:  Entering

root 08:54:53 INFO   :......term_policyAPI: APITerminate:  Exiting

root 08:54:53 INFO   :......term_policyAPI: Policy API terminated
root 08:54:53 INFO   :......dreg_process: deregistering process with the system
root 08:54:53 INFO   :......dreg_process: attempt to dereg (ifaeddrg_byaddr)
root 08:54:53 INFO   :......dreg_process: rc from ifaeddrg_byaddr  rc =0
root 08:54:53 INFO   :.....terminator: process terminated with exit code 0
C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin>type use.log
El sistema no puede encontrar el archivo especificado.

C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin>type user.log
 01
root 08:51:01 INFO   :.main: *************** RSVP Agent started ***************
 02
root 08:51:01 INFO   :...locate_configFile: Specified configuration file: /u/user10/rsvpd1.conf
root 08:51:01 INFO   :.main: Using log level 511
root 08:51:01 INFO   :..settcpimage: Get TCP images rc - EDC8112I Operation not supported on socket.
 03
root 08:51:01 INFO   :..settcpimage: Associate with TCP/IP image name = TCPCS
root 08:51:02 INFO   :..reg_process: registering process with the system
root 08:51:02 INFO   :..reg_process: attempt OS/390 registration
root 08:51:02 INFO   :..reg_process: return from registration rc=0
 04
root 08:51:10 TRACE  :...read_physical_netif: Home list entries returned = 7
root 08:51:10 INFO   :...read_physical_netif: index #0, interface VLINK1 has address 129.1.1.1, ifidx 0
root 08:51:10 INFO   :...read_physical_netif: index #1, interface TR1 has address 9.37.65.139, ifidx 1
root 08:51:10 INFO   :...read_physical_netif: index #2, interface LINK11 has address 9.67.100.1, ifidx 2
root 08:51:10 INFO   :...read_physical_netif: index #3, interface LINK12 has address 9.67.101.1, ifidx 3
root 08:51:10 INFO   :...read_physical_netif: index #4, interface CTCD0 has address 9.67.116.98, ifidx 4
root 08:51:10 INFO   :...read_physical_netif: index #5, interface CTCD2 has address 9.67.117.98, ifidx 5
root 08:51:10 INFO   :...read_physical_netif: index #6, interface LOOPBACK has address 127.0.0.1, ifidx 0
root 08:51:10 INFO   :....mailslot_create: creating mailslot for timer
root 08:51:10 INFO   :...mailbox_register: mailbox allocated for timer
 05
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
 06
root 08:51:10 WARNING:.....mailslot_create: setsockopt(MCAST_ADD) failed - EDC8116I Address not available.
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 129.1.1.1, entity for rsvp allocated and initialized
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 WARNING:.....mailslot_create: setsockopt(MCAST_ADD) failed - EDC8116I Address not available.
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 9.37.65.139, entity for rsvp allocated and
initialized
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 WARNING:.....mailslot_create: setsockopt(MCAST_ADD) failed - EDC8116I Address not available.
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 9.67.100.1, entity for rsvp allocated and initialized
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 WARNING:.....mailslot_create: setsockopt(MCAST_ADD) failed - EDC8116I Address not available.
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 9.67.101.1, entity for rsvp allocated and initialized
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 9.67.116.98, entity for rsvp allocated and
initialized
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 9.67.117.98, entity for rsvp allocated and
root 08:51:03 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:034 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:043 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:04 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......JPG Fyletype has removed: creating mailslot for RSVP
root 08:51:10 INFO   :......dir has removed: creating mailslot for RSVP
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp
root 08:51:10 INFO   :.....mailslot_create: creating mailslot for RSVP via UDP
root 08:51:10 INFO   :....mailbox_register: mailbox allocated for rsvp-udp
root 08:51:10 TRACE  :..entity_initialize: interface 127.0.0.1, entity for rsvp allocated and initialized
root 08:51:10 INFO   :......mailslot_create: creating socket for querying route
root 08:51:10 INFO   :.....mailbox_register: no mailbox necessary for forward
root 08:51:10 INFO   :......mailslot_create: creating mailslot for route engine - informational socket
root 08:51:10 TRACE  :......mailslot_create: ready to accept informational socket connection
root 08:51:11 INFO   :.....mailbox_register: mailbox allocated for route
root 08:51:11 INFO   :.....mailslot_create: creating socket for traffic control module
root 08:51:11 INFO   :....mailbox_register: no mailbox necessary for traffic-control
root 08:51:11 INFO   :....mailslot_create: creating mailslot for RSVP client API
root 08:51:11 INFO   :...mailbox_register: mailbox allocated for rsvp-api
root 08:51:11 INFO   :...mailslot_create: creating mailslot for terminate
root 08:51:11 INFO   :..mailbox_register: mailbox allocated for terminate
root 08:51:11 INFO   :...mailslot_create: creating mailslot for dump
root 08:51:11 INFO   :..mailbox_register: mailbox allocated for dump
root 08:51:11 INFO   :...mailslot_create: creating mailslot for (broken) pipe
root 08:51:11 INFO   :..mailbox_register: mailbox allocated for pipe
 07
root 08:51:11 INFO   :.main: rsvpd initialization complete
 08
root 08:52:50 INFO   :......rsvp_api_open: accepted a new connection for rapi
root 08:52:50 INFO   :.......mailbox_register: mailbox allocated for mailbox
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 does not exist
 09
root 08:52:50 EVENT  :.....api_reader: api request SESSION
 10
root 08:52:50 TRACE  :......rsvp_event_establishSession: local node will send
root 08:52:50 INFO   :........router_forward_getOI: Ioctl to get route entry successful
root 08:52:50 TRACE  :........router_forward_getOI:         source address:   9.67.116.98
root 08:52:50 TRACE  :........router_forward_getOI:         out inf:   9.67.116.98
root 08:52:50 TRACE  :........router_forward_getOI:         gateway:   0.0.0.0
root 08:52:50 TRACE  :........router_forward_getOI:         route handle:   7f5251c8
 11
root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22
 root 08:52:50 TRACE  :.......event_establishSessionSend: found outgoing if=9.67.116.98 through
forward engine
root 08:52:50 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 12
root 08:52:50 EVENT  :.....api_reader: api request SENDER
 13
root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Entering

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  papiLogFunc = 98681F0 papiUserValue = 0

root 08:52:50 INFO   :.......init_policyAPI: papi_debug:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Entering

root 08:52:50 INFO   :.......init_policyAPI: open_socket:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  ApiHandle = 98BDFB0,  connfd = 22

root 08:52:50 INFO   :.......init_policyAPI: APIInitialize:  Exiting

root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Entering
root 08:52:50 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Writing to socket = 22

root 08:52:50 INFO   :.......init_policyAPI: ReadBuffer:  Entering

root 08:52:51 INFO   :.......init_policyAPI: ReadBuffer:  Exiting

root 08:52:51 INFO   :.......init_policyAPI: RegisterWithPolicyAPI:  Exiting
root 08:52:51 INFO   :.......init_policyAPI: Policy API initialized
root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindActionName:  Entering

root 08:52:51 INFO   :......rpapi_getPolicyData: ReadBuffer:  Entering

root 08:52:51 INFO   :......rpapi_getPolicyData: ReadBuffer:  Exiting

root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindActionName:  Result = 0

root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindActionName:  Exiting

 14
root 08:52:51 INFO   :......rpapi_getPolicyData: found action name CLCat2 for
flow[sess=9.67.116.99:1047:6,source=9.67.116.98:8000]
root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindServiceDetailsOnActName:  Entering

root 08:52:51 INFO   :......rpapi_getPolicyData: ReadBuffer:  Entering

root 08:52:51 INFO   :......rpapi_getPolicyData: ReadBuffer:  Exiting

root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindServiceDetailsOnActName:  Result = 0

root 08:52:51 INFO   :......rpapi_getPolicyData: RSVPFindServiceDetailsOnActName:  Exiting

root 08:52:51 INFO   :.....api_reader: appl chose service type 1
root 08:52:51 INFO   :......rpapi_getSpecData: RSVPGetTSpec:  Entering

root 08:52:51 INFO   :......rpapi_getSpecData: RSVPGetTSpec:  Result = 0

root 08:52:51 INFO   :......rpapi_getSpecData: RSVPGetTSpec:  Exiting

root 08:52:51 TRACE  :.....api_reader: new service=1, old service=0
root 08:52:51 INFO   :.......rsvp_flow_stateMachine: state SESSIONED, event PATHDELTA
 15
root 08:52:51 TRACE  :........rsvp_action_nHop: constructing a PATH
root 08:52:51 TRACE  :........flow_timer_start: started T1
 16
root 08:52:51 TRACE  :.......rsvp_flow_stateMachine: entering state PATHED
root 08:52:51 TRACE  :........mailslot_send: sending to (9.67.116.99:0)
root 08:52:51 TRACE  :........mailslot_send: sending to (9.67.116.99:1698)
 17
root 08:52:51 TRACE  :.....rsvp_event: received event from RAW-IP on interface 9.67.116.98
root 08:52:51 TRACE  :......rsvp_explode_packet: v=1,flg=0,type=2,cksm=54875,ttl=255,rsv=0,len=84
root 08:52:51 TRACE  :.......rsvp_parse_objects: STYLE is WF
root 08:52:51 INFO   :.......rsvp_parse_objects: obj RSVP_HOP hop=9.67.116.99, lih=0
root 08:52:51 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
root 08:52:51 INFO   :.......rsvp_flow_stateMachine: state PATHED, event RESVDELTA
 18
root 08:52:51 TRACE  :........traffic_action_oif: is to install filter
root 08:52:51 INFO   :.........qosmgr_request: src-9.67.116.98:8000 dst-9.67.116.99:1047 proto-6
rthdl-7f5251c8
 19
root 08:52:51 INFO   :.........qosmgr_request: [CL r=90000 b=6000 p=110000 m=1024 M=2048]
root 08:52:51 INFO   :.........qosmgr_request: Ioctl to add reservation successful
root 08:52:51 INFO   :..........rpapi_Reg_UnregFlow: RSVPPutActionName:  Entering
root 08:52:51 INFO   :..........rpapi_Reg_UnregFlow: ReadBuffer:  Entering

root 08:52:52 INFO   :..........rpapi_Reg_UnregFlow: ReadBuffer:  Exiting

root 08:52:52 INFO   :..........rpapi_Reg_UnregFlow: RSVPPutActionName:  Result = 0

root 08:52:52 INFO   :..........rpapi_Reg_UnregFlow: RSVPPutActionName:  Exiting

root 08:52:52 INFO   :..........rpapi_Reg_UnregFlow: flow[sess=9.67.116.99:1047:6,
source=9.67.116.98:8000] registered with CLCat2
root 08:52:52 EVENT  :..........qosmgr_response: RESVRESP from qosmgr, reason=0, qoshandle=8b671d0
root 08:52:52 INFO   :..........qosmgr_response: src-9.67.116.98:8000 dst-9.67.116.99:1047 proto-6
root 08:52:52 TRACE  :...........traffic_reader: tc response msg=1, status=1
root 08:52:52 INFO   :...........traffic_reader: Reservation req successful[session=9.67.116.99:1047:6,
source=9.67.116.98:8000, qoshd=8b671d0]
 20
root 08:52:52 TRACE  :........api_action_sender: constructing a RESV
root 08:52:52 TRACE  :........flow_timer_stop: stopped T1
root 08:52:52 TRACE  :........flow_timer_stop: Stop T4
root 08:52:52 TRACE  :........flow_timer_start: started T1
root 08:52:52 TRACE  :........flow_timer_start: Start T4
 21
root 08:52:52 TRACE  :.......rsvp_flow_stateMachine: entering state RESVED
 22
root 08:53:07 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:07 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:07 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:07 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:07 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:07 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:07 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:07 TRACE  :.......flow_timer_start: started T1
root 08:53:07 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:07 TRACE  :.......mailslot_send: sending to (9.67.116.99:0) 20
root 08:52:52 TRACE  :........api_action_sender: constructing a RESV
root 08:52:52 TRACE  :........flow_timer_stop: stopped T1
root 08:52:52 TRACE  :........flow_timer_stop: Stop T4
root 08:52:52 TRACE  :........flow_timer_start: started T1
root 08:52:52 TRACE  :........flow_timer_start: Start T4
 21
root 08:52:52 TRACE  :.......rsvp_flow_stateMachine: entering state RESVED
 22
root 08:53:07 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:07 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:07 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:07 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:07 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:07 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:07 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:07 TRACE  :.......flow_timer_start: started T1
root 08:53:07 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:07 TRACE  :.......mailslot_send: sending to (9.67.116.99:0) 20
root 08:52:52 TRACE  :........api_action_sender: constructing a RESV
root 08:52:52 TRACE  :........flow_timer_stop: stopped T1
root 08:52:52 TRACE  :........flow_timer_stop: Stop T4
root 08:52:52 TRACE  :........flow_timer_start: started T1
root 08:52:52 TRACE  :........flow_timer_start: Start T4
 21
root 08:52:52 TRACE  :.......rsvp_flow_stateMachine: entering state RESVED
 22
root 08:53:07 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:07 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:07 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:07 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:07 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:07 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:07 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:07 TRACE  :.......flow_timer_start: started T1
root 08:53:07 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:07 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
 23
root 08:53:22 TRACE  :.....rsvp_event: received event from RAW-IP on interface 9.67.116.98
root 08:53:22 TRACE  :......rsvp_explode_packet: v=1,flg=0,type=2,cksm=54875,ttl=255,rsv=0,len=84
root 08:53:22 TRACE  :.......rsvp_parse_objects: STYLE is WF
root 08:53:22 INFO   :.......rsvp_parse_objects: obj RSVP_HOP hop=9.67.116.99, lih=0
root 08:53:22 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
root 08:53:22 INFO   :.......rsvp_flow_stateMachine: state RESVED, event RESV
root 08:53:22 TRACE  :........flow_timer_stop: Stop T4
root 08:53:22 TRACE  :........flow_timer_start: Start T4
root 08:53:22 TRACE  :.......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:22 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:22 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:22 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:22 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:22 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:22 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:22 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:22 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:22 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:22 TRACE  :.......flow_timer_start: started T1
root 08:53:22 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:22 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:53:38 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:38 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:38 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:38 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:38 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:38 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:38 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:38 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:38 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:38 TRACE  :.......flow_timer_start: started T1
root 08:53:38 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:38 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:53:52 TRACE  :.....rsvp_event: received event from RAW-IP on interface 9.67.116.98
root 08:53:52 TRACE  :......rsvp_explode_packet: v=1,flg=0,type=2,cksm=54875,ttl=255,rsv=0,len=84
root 08:53:52 TRACE  :.......rsvp_parse_objects: STYLE is WF
root 08:53:52 INFO   :.......rsvp_parse_objects: obj RSVP_HOP hop=9.67.116.99, lih=0
root 08:53:52 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
root 08:53:52 INFO   :.......rsvp_flow_stateMachine: state RESVED, event RESV
root 08:53:52 TRACE  :........flow_timer_stop: Stop T4
root 08:53:52 TRACE  :........flow_timer_start: Start T4
root 08:53:52 TRACE  :.......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:53 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:53 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:53 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:53 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:53 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:53 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:53 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:53 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:53 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:53 TRACE  :.......flow_timer_start: started T1
root 08:53:53 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:53 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:54:09 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:54:09 TRACE  :.....event_timerT1_expire: T1 expired
root 08:54:09 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:54:09 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:54:09 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:54:09 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:54:09 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:54:09 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:54:09 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:54:09 TRACE  :.......flow_timer_start: started T1
root 08:54:09 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:54:09 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:54:22 TRACE  :.....rsvp_event: received event from RAW-IP on interface 9.67.116.98
root 08:54:22 TRACE  :......rsvp_explode_packet: v=1,flg=0,type=2,cksm=54875,ttl=255,rsv=0,len=84
root 08:54:22 TRACE  :.......rsvp_parse_objects: STYLE is WF
root 08:54:22 INFO   :.......rsvp_parse_objects: obj RSVP_HOP hop=9.67.116.99, lih=0
root 08:54:22 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
root 08:54:22 INFO   :.......rsvp_flow_stateMachine: state RESVED, event RESV
root 08:54:22 TRACE  :........flow_timer_stop: Stop T4
root 08:54:22 TRACE  :........flow_timer_start: Start T4
root 08:54:22 TRACE  :.......rsvp_flow_stateMachine: reentering state RESVED
root 08:54:24 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:54:24 TRACE  :.....event_timerT1_expire: T1 expired
root 08:54:24 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:54:24 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:54:24 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:54:24 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:54:24 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:54:24 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:54:24 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:54:24 TRACE  :.......flow_timer_start: started T1
root 08:54:24 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:54:24 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:54:35 TRACE  :......rsvp_event_mapSession: Session=9.67.116.99:1047:6 exists
 24
root 08:54:35 EVENT  :.....api_reader: api request SENDER_WITHDRAW
root 08:54:35 INFO   :.......rsvp_flow_stateMachine: state RESVED, event PATHTEAR
 25
root 08:54:35 TRACE  :........traffic_action_oif: is to remove filter 20
root 08:52:52 TRACE  :........api_action_sender: constructing a RESV
root 08:52:52 TRACE  :........flow_timer_stop: stopped T1
root 08:52:52 TRACE  :........flow_timer_stop: Stop T4
root 08:52:52 TRACE  :........flow_timer_start: started T1
root 08:52:52 TRACE  :........flow_timer_start: Start T4
 21
root 08:52:52 TRACE  :.......rsvp_flow_stateMachine: entering state RESVED
 22
root 08:53:07 EVENT  :..mailslot_sitter: process received signal SIGALRM
root 08:53:07 TRACE  :.....event_timerT1_expire: T1 expired
root 08:53:07 INFO   :......router_forward_getOI: Ioctl to query route entry successful
root 08:53:07 TRACE  :......router_forward_getOI:         source address:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         out inf:   9.67.116.98
root 08:53:07 TRACE  :......router_forward_getOI:         gateway:   0.0.0.0
root 08:53:07 TRACE  :......router_forward_getOI:         route handle:   7f5251c8
root 08:53:07 INFO   :......rsvp_flow_stateMachine: state RESVED, event T1OUT
root 08:53:07 TRACE  :.......rsvp_action_nHop: constructing a PATH
root 08:53:07 TRACE  :.......flow_timer_start: started T1
root 08:53:07 TRACE  :......rsvp_flow_stateMachine: reentering state RESVED
root 08:53:07 TRACE  :.......mailslot_send: sending to (9.67.116.99:0)
root 08:54:35 INFO   :.........qosmgr_request: Ioctl to remove reservation successful
root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: RSVPRemActionName:  Entering

root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: ReadBuffer:  Entering

root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: ReadBuffer:  Exiting

root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: RSVPRemActionName:  Result = 0

root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: RSVPRemActionName:  Exiting

root 08:54:35 INFO   :..........rpapi_Reg_UnregFlow: flow[sess=9.67.116.99:1047:6,
source=9.67.116.98:8000] unregistered from CLCat2
root 08:54:35 EVENT  :..........qosmgr_response: DELRESP from qosmgr, reason=0, qoshandle=0
root 08:54:35 INFO   :..........qosmgr_response: src-9.67.116.98:8000 dst-9.67.116.99:1047 proto-6
root 08:54:35 TRACE  :...........traffic_reader: tc response msg=3, status=1
 26
root 08:54:35 TRACE  :........rsvp_action_nHop: constructing a PATHTEAR
root 08:54:35 TRACE  :........flow_timer_stop: stopped T1
root 08:54:35 TRACE  :........flow_timer_stop: Stop T4
 27
root 08:54:35 TRACE  :.......rsvp_flow_stateMachine: entering state SESSIONED
root 08:54:35 TRACE  :........mailslot_send: sending to (9.67.116.99:0)
root 08:54:35 TRACE  :......rsvp_event_propagate: flow[session=9.67.116.99:1047:6,
source=9.67.116.98:8000] ceased
 28
root 08:54:35 EVENT  :.....api_reader: api request CLOSE
root 08:54:35 INFO   :.......rsvp_flow_stateMachine: state SESSIONED, event PATHTEAR
root 08:54:35 PROTERR:.......rsvp_flow_stateMachine: state SESSIONED does not expect event PATHTEAR
 29
root 08:54:53 EVENT  :..mailslot_sitter: process received signal SIGTERM
root 08:54:53 INFO   :...check_signals: received TERM signal
root 08:54:53 INFO   :......term_policyAPI: UnRegisterFromPolicyAPI:  Entering

root 08:54:53 INFO   :......term_policyAPI: ReadBuffer:  Entering

root 08:54:53 INFO   :......term_policyAPI: ReadBuffer:  Exiting

root 08:54:53 INFO   :......term_policyAPI: UnRegisterFromPolicyAPI:  Result = 0

root 08:54:53 INFO   :......term_policyAPI: UnRegisterFromPolicyAPI:  Exiting

root 08:54:53 INFO   :......term_policyAPI: APITerminate:  Entering

root 08:54:53 INFO   :......term_policyAPI: APITerminate:  Exiting

root 08:54:53 INFO   :......term_policyAPI: Policy API terminated
root 08:54:53 INFO   :......dreg_process: deregistering process with the system
root 08:54:53 INFO   :......dreg_process: attempt to dereg (ifaeddrg_byaddr)
root 08:54:53 INFO   :......dreg_process: rc from ifaeddrg_byaddr  rc =0
root 08:54:53 INFO   :.....terminator: process terminated with exit code 0
C:\Users\Isacc\Downloads\curl-7.83.1_3-win64-mingw\bin>
