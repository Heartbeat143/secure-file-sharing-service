# secure-file-sharing-service

[NOTE:-The Work is result of my Internship in crio lunch program of the Crio.Do company.]

QBox is a secure file-sharing service. It is a customized version of the popularly available VSFTPD server. During the course of this Micro-Experience:    
  i. We Created pre-install scripts to run system checks, install and configure QBox.    
  ii. Developed tools to automatically analyze performance and functionality issues in different versions of QBox.    

1. Debug performance issues and identify regressions:   
    i. Created a performance benchmark using a base version of QBox.    
    ii. Identified regressions in newer QBox versions (memory usage, cpu usage, file transfer speed, file permission issues).

2, Troubleshoot network issues:   
    i. Collected and analyzed pcap files using Wireshark.    
    ii. Identified the following network issues in different versions of QBox: TCP retransmissions, connection refusals, dropped connections, sub-optimal TCP window sizes and retransmission delays.   
    iii. Identified several network issues in different versions of QBox including TCP retransmissions, connection refusals and retransmission delays.   

3. Enable end-to-end encryption:    
    i. Created SSL certificates and used them to enable secured file transfer.   
    ii. Snooped network traffic using Wireshark and ensured that it was indeed encrypted.   
