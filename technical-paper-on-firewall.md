---
title: Firewall
---

# Firewall



* A firewall is a security device or software.
* Its primary function is to monitor and control incoming and outgoing network traffic based on predetermined security rules. 
How Does a Firewall Work?

## How Does a Firewall Work?

* It filters the network traffic within a private network. It analyses which traffic should be allowed or restricted based on a set of rules.
* It is like a gatekeeper at your computer’s entry point, which only allows trusted sources, or IP addresses, to enter your network 
* It welcomes only incoming traffic that has been configured to accept. 
* It blocks malicious traffic from entering the private network, thereby protecting the user’s network from being susceptible to a cyberattack.
* It also performs basic network-level functions such as NAT and VPN

    **NAT** - Network Address Translation hides or translates internal client or server IP addresses that may be in a private address range.

    **VPN** -  Virtual Private Network extends a private network across a public network within a tunnel that is often encrypted where the contents of the packets are protected while traversing the Internet.

    ![How Does a Firewall Work](https://www.simplilearn.com/ice9/free_resources_article_thumb/Firewall_2.png)


### Software Firewall

* It is implemented and operated through software running on a computer or network device.
* It is designed to monitor and control network traffic by enforcing predetermined security rules and policies.

### Hardware Firewall

* It is a physical device that sits between a private internal network and external networks, such as the Internet.
* It provides an additional layer of protection for the network by filtering out potential threats, unauthorized access attempts, and malicious activities.

## Types of firewalls

### Packet Filtering Firewalls

* They check a data packet for its source IP and destination IP, the protocol, source port, and destination port against predefined rules to determine whether to pass or discard the packet.
* They monitor each packet independently without any track of the established connection or the packets that have passed through that connection previously.
* They are the oldest, most basic type of firewall.

    **data packet** - It is a basic unit of information that is transmitted over a network.

### Application-Level Gateways (Proxy Firewalls)

* They are implemented at the application layer via a proxy device.
* Instead of an outsider accessing your internal network directly, the connection is established through the proxy firewall.
* After verifying the authenticity of the request, the proxy firewall forwards it to one of the internal devices or servers on the client’s behalf.
* They are suitable for educational institutions, government organizations, or for various individuals and organizations 

### Next-Generation Firewalls
* They perform deep packet inspection in addition to port/protocol and surface-level packet inspection.
* They combine the features of other types of firewalls into a single solution without affecting network performance.
* They are suitable for businesses that need to comply with the Health Insurance Portability and Accountability Act (HIPAA) or payment card industry (PCI) rules or for those that want multiple security features integrated into a single solution. 

---

## References

* [Firewall/youtube](https://www.youtube.com/watch?v=fCM86XAyQ7o&list=PLBbU9-SUUCwV7Dpk7GI8QDLu3w54TNAA6&index=5)

* [What is firewall by checkpoint.com](https://www.checkpoint.com/cyber-hub/network-security/what-is-firewall/)

* [Types of firewalls by parallels.com](https://www.parallels.com/blogs/ras/types-of-firewalls/)

* [How Does a Firewall Work ](https://www.simplilearn.com/ice9/free_resources_article_thumb/Firewall_2.png)