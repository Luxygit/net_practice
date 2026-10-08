*This project has been created as part of the 42 curriculum by dievarga*

# Net_Practice

## Description
This is an introduction to TCP/IP networking, where we simulate some
connections between hosts, switches, routers and the internet.
Each level makes the network more complex and demands more knowledge
about TCP, private/public IPs, subnet masks, routing.

## Instructions
To start the evaluation simply download and extract the net_practice.tgz
and inside the folder execute run.sh.
This tool is meant on one part to practice the mentioned networking
concepts and the other part to use during the evaluation where the
student needs to complete 3 proper networks.
There is a button at the top to export your network configuration json
file for every level solved, a total of 10 files must be exported and
located at the root of the repository.

##Resources

- TCP/IP
Transfer Control Protocol is a standard that lets computers communicate
over a network. It is part of the OSI model.
It is slower than UDP but prefered over this one for several internet
applications because of its more strict control and verification of the
connection to be stablished.

- Subnet maks
Since there is only a limited number of addresses for the 32-bit IPv4
standard, dividing the spectrum of these in a network can be useful
to isolate smaller parts of the network.
This is shown in 2 notations, dotted decimal"255.255.255.0" 
or CIRD "/24" notation.
The first address of the mask is reserved as the network address or
identifier and the last one is the broadcast address that sends
data to all devices.

- Default gateways
These are the exit points for data going from a local network to
an external network.
This is used in case the device routing has no specific rule as 
a destination address.

- OSI layers
The open system interconnection model is a framework that makes sure 
data is properly packed and sent and received by two devices.
It starts from the first application layer all the way out to the
physical layer (cable, wifi) and then unpacked by the receiver again.

- Routers
This is the device that connects devices over different networks.
It can connect a group of devices to the internet, directs traffic,
assign dynamic addresses, translates private to public addresses, etc.

- Switches
To connect devices within a local network, switches are used. 
These look at the MAC media access control addresses of every device
instead of their private IP.
