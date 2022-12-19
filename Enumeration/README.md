# 👀 Enumeration Overview
  Enumeration is one of the beginning phases of a penetration test. This is where we look for the services that are running and attempt to gather information about those services.
  This can include information on login credentials, misconfigured services and understanding the attack surface of a system/network. Below I outline the main tools for enumeration and how to gather information on 5 common services: SMB, FTP, SSH, HTTP, and SQL.
  

## SMB
**What is SMB?**
<p>Server Message Block (SMB) is essentially a communication protocol operating at the application layer. It enables clients to ‘talk’ to a server. It is primarily on Windows systems while macOS and Linux run clients to connect to an SMB server. It makes it possible for remote users to access data on the server. Furthermore, it enables remote access to other resources such as printers.</p>

[SMB Enumeration Basics](https://github.com/jmeliendrez/ejptv2/blob/main/Enumeration/Basics/SMB%20Enumeration%20Basic.md)

**Further Reading**
<p>Here are a few articles I found helpful in understanding the protocol. It's important to understand the technology you are testing.</p>

- [Wikipedia Article](https://en.wikipedia.org/wiki/Server_Message_Block)

- [TechTarget Article](https://www.techtarget.com/searchnetworking/definition/Server-Message-Block-Protocol)

- [NordVPN Article](https://nordvpn.com/blog/what-is-smb/)

## FTP
**What is FTP?**
<p>The File Transfer Protocol (FTP), as the name suggests, enables clients to transfer files using a client-server model. FTP works by establishing either an active of passive connection with the FTP server. In an active connection, FTP utilises TCP to establish and maintain a connection. In a passive connection, FTP opens two ports (port > 1023) to establish a connection and send/receive data. For example, FTP with open ports 2222 and 2223. On port 2222 the FTP client will issue commands and port 2223 is utilised for data transfer. FTP is inherently insecure due to unencrypted connections. Due to this SFTP (SSH File Transfer Protocol) was developed.</p>

[FTP Enumeration Basics](https://github.com/jmeliendrez/ejptv2/blob/main/Enumeration/Basics/FTP%20Enumeration%20Basics.md)

**Further Reading**
<p>Here are a few articles I found helpful in understanding the protocol.</p>

- [Wikipedia Article](https://en.wikipedia.org/wiki/File_Transfer_Protocol)

- [RFC 959: FTP](https://datatracker.ietf.org/doc/html/rfc959)

- [TechTarget Article](https://www.techtarget.com/searchnetworking/definition/File-Transfer-Protocol-FTP)

## SSH
**What is SSH?**
<p></p>

[SSH Enumeration Basics](https://github.com/jmeliendrez/ejptv2/blob/main/Enumeration/Basics/SSH%20Enumeration%20Basics.md)

## HTTP
**What is HTTP?**
<p></p>

[HTTP Enumeration Basics](https://github.com/jmeliendrez/ejptv2/blob/main/Enumeration/Basics/HTTP%20Enumeration%20Basics.md)

## SQL
**What is SQL?**
<p></p>

[SQL Enumeration Basics](https://github.com/jmeliendrez/ejptv2/blob/main/Enumeration/Basics/SQL%20Enumeration%20Basics.md)
