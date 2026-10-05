Created a Windows Server virtual machine that a configured as the domain controller.
Configured DHCP on the Windows Server to assign IP addresses for every endpoint connected to the network.
Configured Active Directory on the Windows Server and created a local domain and multiple users in said "work" domain.
Created one Admin user that has Admin privileges and can use the Domain controller to configure DHCP settings and GPO.
Created a Windows 11 virtual machine that connects to the internet via the domain controller, as the domain controller gave the Win 11 VM the first free IP address from the IP range that I made available.
Configured the Win 11 VM for one of the users I created earlier, whom did not have admin privileges.
