# Operational Security Management
<h1> Managing Windows Accounts and Organizational Units </h1>
<h2> Overview </h2>
<p>
  I gained hands-on experience in this lab implementing an access control system using Microsoft Active Directory (AD). AD is a user and computer structure introduced by Microsoft and utilized in many Windows-centric environments. It employs the LDAP format for its database, facilitating a directory tree structure for user accounts and groups. AD enables administrators to control user and computer access to network resources, ensuring security.

I learned to build hierarchical directory structures in AD, simplifying user-resource allocation. For instance, I could regulate printer access in a corporate setting, ensuring only authorized personnel can use specific printers. The concept of Organizational Units (OUs) in AD allows for efficient resource sharing between companies within a forest.

During the lab, I performed various AD and OU administrative tasks. Using the Microsoft Active Directory Users and Computers interface, I created new user accounts and OUs, adhering to good account management practices. Additionally, I practiced deleting existing user accounts and replicating real-world network administration scenarios.
</p>
<h2> Tools Used </h2>
<p>
  In the lab, I utilized several tools and interfaces to perform Active Directory (AD) and Organizational Unit (OU) administrative tasks:
</p>
<ul>
  <li> <strong> Microsoft Active Directory Users and Computers:</strong> This interface served as the primary tool for managing user accounts, groups, and organizational units within the Active Directory environment. It provided a graphical user interface (GUI) for creating, modifying, and deleting user accounts and OUs. </li>
  <li> <strong> Microsoft Active Directory:</strong> As the core access control system, Microsoft Active Directory provides the underlying infrastructure for performing authentication, authorization, and accounting activities. It allowed me to create and manage user accounts, groups, and resources across the network. </li>
  <li> <srong> LDAP (Lightweight Directory Access Protocol):</srong> Although not a standalone tool, LDAP played a crucial role in the functioning of Active Directory. It provided the underlying protocol for accessing and managing directory services, enabling the hierarchical organization of user accounts and groups. </li>
  <li> <strong> Windows Server Environment:</strong> Since Active Directory is tightly integrated with the Windows Server operating system, I  worked within a Windows Server environment to access and manage Active Directory services. This environment provided the necessary infrastructure for hosting and managing Active Directory domains. </li>
  <li> <strong> Administrative Privileges:</strong> While not a specific tool, administrative privileges were essential for performing administrative tasks within Active Directory. These privileges allowed me to create, modify, and delete user accounts, groups, and organizational units. </li>
</ul>

<h1> Configuring a Remote Access VPN </h1>
<h2> Overview </h2>
<p>
  I set up a Virtual Private Network (VPN) in this lab using the technology integrated into Microsoft Windows Server 2019. VPNs are essential for ensuring perimeter security, especially for remote employees accessing enterprise resources from untrusted networks. By encrypting network traffic, VPNs safeguard data from eavesdropping during transmission over the Internet.

The lab focused on configuring the Windows Server 2019 to support a VPN, enabling VPN users on the remote server, and verifying its functionality by connecting from a different Windows system. This hands-on experience provided insights into the setup and management of VPNs, which are increasingly in demand due to the rise of telecommuting and remote working solutions.

By leveraging the VPN technology within Windows Server 2019, organizations can establish secure connections for remote users and networks, enhancing their overall security posture in an increasingly interconnected digital landscape.
</p>
<h2> Tool Used </h2>
<p>
  In this lab, I utilized the following tools and technologies to set up a Virtual Private Network (VPN) using Microsoft Windows Server 2019:
</p>
<ul>
  <li><strong> Microsoft Windows Server 2019: </strong> The core operating system used as the foundation for configuring and hosting the VPN infrastructure. </li>
  <li><strong> VPN Server Configuration: </strong> Within Windows Server 2019, I configured the built-in VPN server functionality to support VPN connections. </li>
  <li><strong> OpenVPN: </strong> OpenVPN is an open-source software application that implements virtual private network (VPN) techniques for creating secure point-to-point or site-to-site connections in routed or bridged configurations and remote access facilities. It's widely used for its flexibility, security, and cross-platform compatibility. </li>
  <li><strong> VPN Client:  </strong> On the remote Windows system, I used the built-in VPN client functionality available in Windows to connect to the VPN server.</li>
  <li><strong> pfSense: </strong> pfSense is a free and open-source firewall and router software distribution based on FreeBSD. It provides a wide range of features, including VPN capabilities, through its intuitive web interface. pfSense is commonly used as a VPN server solution due to its robustness, scalability, and extensive feature set. </li>
</ul>

