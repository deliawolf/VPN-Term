# VPN-Term

A VPN is a technology that secures communication across an untrusted network. As defined in RFC 2828, a VPN is “a restricted-use, logical (that is artificial or simulated) computer network that is constructed from the system resources of a relatively public, physical (that is, real) network (such as the Internet), often by using encryption (located at hosts or gateways), and often by tunneling links of the virtual network across the real network.”

## Simply stated, a VPN can be defined in the following ways:

1. Virtual: Logical networks, independent of physical architecture.

2. Private: Independent of IP addressing and routing schemes (noncryptographic approaches). Secure confidentiality, message integrity, and origin authentication (cryptographic approaches).

3. Network: Interconnected computers, devices, and resources that are grouped to share information.

## Encryption can be implemented with one of the two following methods:

1. Link encryption: The entire frame is encrypted between two devices. This is used on point-to-point connections of directly connected devices.

2. Packet payload encryption: Only the packet payload is encrypted, which allows this form of encryption to be routed across a Layer 3 network, such as the internet.

## To be effective, a cryptographic VPN must provide:

1. Confidentiality: The assurance that no one except the intended recipient can read the data traversing the VPN. The purpose of encryption is to guarantee confidentiality.

2. Origin authentication: The assurance that the endpoint entities are legitimate (who they claim to be).

3. Data integrity: The assurance that data traversing the VPN has not been altered in transit, intentionally or unintentionally.

## VPNs are classified according to the following criteria:

1. Deployment mode: Site-to-site VPN and remote-access VPN. A site-to-site VPN provides an internet-based WAN infrastructure for connecting branch offices, home offices, or the sites of business partners to all or portions of a network. A remote-access VPN provides secure communications for remote access to networks and applications. Hosts can establish remote-access VPNs either by using VPN client software or by using an SSL-enabled web browser.

2. Underlying technology: IPsec VPN, SSL VPN, Multiprotocol Label Switching (MPLS) VPN, other Layer 2 technologies such as Frame Relay or Asynchronous Transfer Mode (ATM), and hybrid VPNs combining multiple technologies.
