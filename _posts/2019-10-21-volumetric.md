---
title: Volumetric attacks an Introspective
---

Just a brief introspective to the attacks that are driven to target bandwidth, and other times target routers, load balancers and firewalls. They get measured as bits per second or packets per second. Some specific volumetric attacks are:

.. **DNS reflection attack:** The attacker sends DNS requests to third-party DNS servers, while spoofing the source IP address and pretending that the requests came from the victim. The requests that the victim sends usually involve amplification – meaning the requests will result in a much larger response. An example is a DNS ANY request, which ask the DNS server for all information that it currently knows about the domain – where the mail servers are (MX records), what the IP addresses are (A records), and so on. This maximizes the size of the response sent to the victim. When the DNS servers send their disproportionately large response to the spoofed source, it results in a huge amount of traffic flooding the victim.

.. **SYN flood attack:** The attacker sends a flood of SYN packets to the victim’s server while spoofing the source IP address, pretending to be sent from someone else. The victim’s server sends back the SYN-ACK message to the sender and never receives an ACK message. The half-open connections created on the server eventually cause the server to run out of resources, making it unable to respond to any requests, including legitimate requests.

.. **Smurf attack:** The attacker uses specially-crafted packets with the victim’s IP as the source IP and sets the destination to the broadcast address of a large network. All of the responses from all of the hosts on that network get sent back to the victim, overwhelming their network and servers.
