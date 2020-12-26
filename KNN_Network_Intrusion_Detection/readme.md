# DOMAIN : NETWORKING   


- ### CONTEXT
  The dataset to be audited was provided which consists of a wide variety of intrusions simulated in a military network environment It created an 
  environment to acquire raw TCP/IP dump data for a network by simulating a typical US Air Force LAN. The LAN was focused like a real environment 
  and blasted with multiple attacks. A connection is a sequence of TCP packets starting and ending at some time duration between which data flows
  to and from a source IP address to a target IP address under some well-defined protocol. Also, each connection is labelled as either normal or as
  an attack with exactly one specific attack type. Each connection record consists of about 100 bytes. For each TCP/IP connection, 41 quantitative 
  and qualitative features are obtained from normal and attack data (3 qualitative and 38 quantitative features) .The class variable has two 
  categories: 
  - Normal 
  - Anomalous


- ### OBJECTIVE
  To detect Network Intrusion using KNN

- ### DATASET
  Network_Intrusion.csv

Variable - Description 

Data basically represents the packet data for a time duration of 2 seconds. 1-9 Columns: basic features of packet (type 1)

10-22 columns: employ the content features (type 2)

23-31 columns: employ the traffic features with 2 seconds of time window (type 4)

32-41 columns: employ the host based features

Feature name Variable type Type Description

1. Duration C 1 No. of seconds of the connection

2. Protocol_type D 1 Type of protocolE.g.: TCP,UDP ,ICMP

3. Service D 1 Network service on the destination E.g.: http, telnet

4. Flag D 1 Normal or error status of the connection

5. src_bytes C 1 Number of data bytes from source to destination

6. dst_bytes C 1 Number of data bytes from destination to source

7. Land D 1 1-connection is from the same host/port:0-otherwise

8. Wrong_fragment C 1 No. of ‘wrong’ fragments

9. Urgent C 1 No of urgent fragments

10.Hot C 2 The count of access to system directories, creation and execution of programs

11.Num_failed_logins C 2 No. of failed login attempts

12.Logged_in D 2 1-successfully logged in0-otherwise

13.num_compromised C 2 No. of compromised conditions

14.Root_shell C 2 1-root shell is obtained;0 otherwise

15.Su_attempted C 2 1-‘su root’ command attempted;0 otherwise

16.Num_root C 2 No .of root accesses

17.num_file_creations C 2 Number of file creation operations

18.Num_shells C 2 No of shell prompts

19.Num_access_files C 2 No. of write ,delete and create operations on access control files

20.Num_outbound_cmds C 2 No. of outbound commands in an ftp session

21.Is_hot_login D 2 1-the login belongs to the ‘hot’ list0: otherwise

22.Count C 3 No. of connections to the same host as the current connection in the past seconds

23.Srv_count C 3 No of connections to the same host as the current connection in the past 2 seconds

24.serror_rate C 3 % of connections that have ‘SYN’ errors to the same host

25.Srv_serror_rate C 3 % of connections that have ‘SYN’ errors to the same service

26.Rerror_rate C 3 % of connections that have ‘REJ’ errors to the same host

27.Srv_diff_host_rate C 3 % of connections to different services and to the same host

28.Dst_host_count C 3 No of connections to the same host to the destination host as the current connection in the past 2 seconds

29.Dst_host_srv_count C 3 No of connections from the same service to the destination host as the current connection in the past 2 seconds

30.dst_host_srv_count C 3 No. of connections from the same service to the destination host as the current connection in the past 2 seconds

31.Dst_host_srv_count C 3 No. of connections from the same service to the destination host as the current connection in the past 2 seconds

32.Dst_host_same_srv_rate C 3 % of connections from the same service to the destination host

33.Dst_host_diff_srv_rate C 3 % of connections from the different services to the destination host

34.Dst_host_same_src_port_rate C 3 % of connections from the port services to the destination host

35.Dst_host_srv_diff_host_rate C 3 % of connections from the different hosts from the same service to destination host

36.Dst_host_serror_rate C 3 % of connections that have ‘SYN” errors to same host to the destination host

37.dst_host_srv_serror_rate C 3 % of connections that have ‘SYN’ errors from the same service to the destination host

38.Dst_host_rerror_rate C 3 % of connections that have ‘REJ’ errors from the same host to destination host

39.Dst_host_srv_rerror_rate C 3 % of connections that have ‘REJ’ errors from the same service to the destination host


- ### Notebook
  KNN_Netwrok_Intrusion_Detection.ipynb