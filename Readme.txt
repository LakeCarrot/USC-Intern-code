# query_test.py
Serve as the controller manager code
usage:
ryu-manager query_test.py
sh tel_connect.sh
1.install flow entries:
test tablesize vlan|mac_dst|ip same_priority| ascending_priority | descending_priority [size]
2.query flow entries:
flowstat datapath [dpid] [loop] [query mode(0-19,33)]
3.show datapath message
show <dpid | ports [dpid]>

# tel_connect.sh
Link to the port 2505

# packet_generate.c
adjust the code to send packet from any device to any IP 
 
# switch_construct.sh
configure the OVS environment 

# test_pcap_processing.c
process the pcap file to get the query time
usage:
./a.out <the pcap file you want to analysis>