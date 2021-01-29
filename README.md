# CMPE-272_Network_Intrusion_Detection

This project is created to build a network intrusion detection program, which is based on wireshark, pyshark. This program detects traffic anomaly based on set rules for TCP, UDP, ICMP, HTTP protocols and send email alerts when this anomaly happens. Currently, the anomaly is based on incoming traffic rate only. In future it can be enhanced to add more rules for anomaly detection.

  ## fileCap:  Analyze pcap file
  ## liveCap: Analyze live traffic
  ## Send_gmail: Send email alert to network monitoring distribution list
  ## ICMP_Ping_of_Death : Monitor icmp packets with size greater than 100 bytes
  ## ICMP_Flood : Monitor network traffic for ICMP flood attack.. 
  ## SYN_Scan: Monitor network traffic for SYN scan attack
  ## SYN_Flood: Monitor network traffic for SYN flood attack
  ## UDP_Flood: Monitor network traffic for UDP flood attack.
  ## Http : Analyze http payload
  ## get_ip4: Get IP address of the target in IPV4 format
  ## get_ip6:  Get IP address of the target in IPV6 format
