APT-SDNdataset is a dataset for APT attacks on SDN network.

APT-SDNmap (https://github.com/APT-SDNmap) is used here to launch attacks in a network using mininet. Hosts (one of them is infected by APT-SDNmap and launched attacks), OVS switch and SDN controller. Ostinato (https://ostinato.org/) is used to generate the normal traffic over different network protocols (ex. TCP, UDP, ICMP, IGMP, and ARP).
There are 3 versions of the dataset here (4 hosts, 8 hosts and 16 hosts).
All network scenarios and attacks are implemented by the same way and the defference is the size of the network.

the dataset fearues are:

No: frame number
time: transaction time
src_ip: source IP
dst_ip: destination IP
protocol: protocol
src_port: source port
dst_port: destination port
eth.type: ethernet type
flag: flag
frame_len: frame length
Src_host_count: average of traffic generated from this source
Src_ARP_count: average of ARP generated from this source
Src_ICMP_count: average of ICMP generated from this source
Src_IGMP_count: average of IGMP generated from this source
Src_TCP_count: average of TCP generated from this source
Src_UDP_count: average of UDP generated from this source
diff_proto_rate: average of different protocol generated from this source
Diff_dest_port: average of destinated ports from this source
TCP: TCP or not
UDP: UDP or not
ICMP: ICMP or not
IGMP: IGMP or not
ARP: ARP or not
label
