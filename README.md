 Operational Security Management - Projects & Labs
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
  <li> <strong> LDAP (Lightweight Directory Access Protocol):</strong> Although not a standalone tool, LDAP played a crucial role in the functioning of Active Directory. It provided the underlying protocol for accessing and managing directory services, enabling the hierarchical organization of user accounts and groups. </li>
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
<h1> Enabling Audit Trails to Enforce Accountability </h1>
<h2> Overview </h2>
<p>
  In this lab, I focused on configuring Windows auditing within Microsoft Windows, emphasizing the importance of identity access management (IAM) systems in maintaining accountability for users' actions.

Auditing plays a critical role in enforcing accountability by generating system logs, known as audit trails, which record essential details such as the date and time of actions, the identity of individuals involved, and other relevant information crucial for cybersecurity investigations.

Using Windows' comprehensive auditing and logging functionality, I configured the system to track user login attempts and file system access. This involved precise configuration of the types of actions to be audited, including options to log successful events, unsuccessful attempts, or both.

After configuring auditing settings, I generated several events to trigger audit records and utilized the Event Viewer tool within Windows to locate and review the corresponding audit logs. Additionally, I explored the option of feeding this information into a Security Information and Event Management (SIEM) solution for further correlation and analysis, highlighting the potential for more advanced security monitoring and incident response capabilities.

This hands-on lab experience gave me practical insights into configuring and utilizing Windows auditing features, enhancing my understanding of IAM principles and their role in maintaining system accountability and cybersecurity.
</p>
<h2> Tools Used </h2>
<ul>
  <li><strong> Microsoft Windows Operating System: </strong> The lab was conducted within a Microsoft Windows environment, specifically focusing on features related to auditing and logging functionality provided by the Windows operating system. </li>
  <li><strong> Windows Auditing and Logging Functionality: </strong> Windows includes a comprehensive auditing and logging functionality that allows administrators to configure the types of actions to be audited, such as user login attempts and file system access. This built-in functionality forms the core of the lab's objective </li>
  <li><strong> Event Viewer Tool: </strong> The Event Viewer tool is a built-in Windows application used for viewing and analyzing event logs generated by the operating system and applications. It provides a graphical interface for navigating through event logs and inspecting individual events. </li>
  <li><strong> PowerShell: </strong> PowerShell is a powerful scripting language provided by Microsoft, commonly used for automation and system administration tasks. In this lab, PowerShell is used to configure auditing settings or perform additional administrative tasks related to the lab objectives. </li>
  <li><strong> Remote Desktop Protocol (RDP):  </strong> RDP is a proprietary protocol developed by Microsoft that allows users to connect remotely to Windows-based systems over a network connection. RDP has been used in this lab to remotely access and manage Windows servers or workstations to configure audit settings and perform other tasks. </li>
</ul>

<h1> Appling the Security Policy Framework to an Access Control Environment </h1>
<h2> Overview </h2>
<p>
  I applied the security policy framework to an access control environment in this lab. The lab emphasized the significance of security policies, standards, guidelines, and procedures in shaping an organization's cybersecurity efforts.
</p>
<h2>Security Policy Framework Overview</h2>
  <ul>
    <li><strong>Policies:</strong> High-level statements outlining the organization's security objectives and principles. Compliance is mandatory.</li>
    <li><strong>Standards:</strong> Detailed requirements for specific situations. Compliance is mandatory.</li>
    <li><strong>Guidelines:</strong> Suggested best practices for achieving security objectives. Compliance is not mandatory but recommended.</li>
    <li><strong>Procedures:</strong> Step-by-step processes for carrying out activities. Compliance may vary based on organizational policies.</li>
  </ul>
  
  <h2>Application of Security Policy Framework</h2>
  <ol>
    <li>
      <h3>Password Policy Review</h3>
      <p>Reviewed sets of best practices for password policies and analyzed real-world password policies. Offered suggestions for improvements.</p>
    </li>
    <li>
      <h3>Security Configuration Standard</h3>
      <p>Reviewed security configuration standards such as NIST SP 800-63b and CIS Microsoft Windows Server 2019 Benchmarks and applied them to production systems.</p>
    </li>
    <li>
      <h3>Procedure Development</h3>
      <p>Wrote a procedure for achieving an access control objective and provided step-by-step guidance for employees.</p>
    </li>
  </ol>
<h2>Useful Resources</h2>
  <ul>
    <li><a href="https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-63b.pdf">NIST SP 800-63b</a></li>
    <li><a href="https://learn.cisecurity.org/benchmarks">CIS: Microsoft Windows Server 2019 Benchmark</a></li>
  </ul>

