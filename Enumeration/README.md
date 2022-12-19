# 👀 Enumeration Overview
  Enumeration is one of the beginning phases of a penetration test. This is where we look for the services that are running and attempt to gather information about those services.
  This can include information on login credentials, misconfigured services and understanding the attack surface of a system/network. Below I outline the main tools for enumeration and how to gather information on 5 common services: SMB, FTP, SSH, HTTP, and SQL.
  

## SMB
**What is SMB?**
<p>Server Message Block (SMB) is essentially a communication protocol operating at the application layer. It enables clients to ‘talk’ to a server. It is primarily on Windows systems while macOS and Linux run clients to connect to an SMB server. It makes it possible for remote users to access data on the server. Furthermore, it enables remote access to other resources such as printers.</p>

[SMB Enumeration Basics](https://github.com/jmeliendrez/ejptv2/blob/main/Enumeration/Basics/SMB%20Enumeration%20Basic.md)

**Further Reading**

- [Wikipedia Article](https://en.wikipedia.org/wiki/Server_Message_Block)

- [TechTarget Article](https://www.techtarget.com/searchnetworking/definition/Server-Message-Block-Protocol)

- [NordVPN Article](https://nordvpn.com/blog/what-is-smb/)

## FTP
**What is FTP?**
<p>The File Transfer Protocol (FTP), as the name suggests, enables clients to transfer files using a client-server model. FTP works by establishing either an active of passive connection with the FTP server. In an active connection, FTP utilises TCP to establish and maintain a connection. In a passive connection, FTP opens two ports (port > 1023) to establish a connection and send/receive data. For example, FTP with open ports 2222 and 2223. On port 2222 the FTP client will issue commands and port 2223 is utilised for data transfer. FTP is inherently insecure due to unencrypted connections. Due to this SFTP (SSH File Transfer Protocol) was developed.</p>

[FTP Enumeration Basics](https://github.com/jmeliendrez/ejptv2/blob/main/Enumeration/Basics/FTP%20Enumeration%20Basics.md)

**Further Reading**

- [Wikipedia Article](https://en.wikipedia.org/wiki/File_Transfer_Protocol)

- [RFC 959: FTP](https://datatracker.ietf.org/doc/html/rfc959)

- [TechTarget Article](https://www.techtarget.com/searchnetworking/definition/File-Transfer-Protocol-FTP)

## SSH
**What is SSH?**
<p>Secure Shell Protocol (SSH) is a secure login connection protocol that functions at the Application layer of the OSI model. It was designed as a replacement for Telnet which was insecure due to plain-text transmission and communication. It is used for remote access via the command-line interface (CLI) in a client-server model. SSH establishes a secure connection using public and private keys. Then it encrypts traffic using symmetric encryption. For more information vie the SSH Academy documentation.</p>

[SSH Enumeration Basics](https://github.com/jmeliendrez/ejptv2/blob/main/Enumeration/Basics/SSH%20Enumeration%20Basics.md)

**Further Reading**

- [SSH Academy](https://www.ssh.com/academy/ssh/protocol)

- [Wikipedia Article](https://en.wikipedia.org/wiki/Secure_Shell)

- [UCL Article](https://www.ucl.ac.uk/isd/what-ssh-and-how-do-i-use-it)

## HTTP
**What is HTTP?**
<p>Hyper-Text Transfer Protocol (HTTP) is the backbone protocol of the Internet. HTTP is used to get pages, images, videos and other data to a client. It is based on a client-serve architecture. Clients request assets from a server and the server responds by delivering the content, if available/authorised. HTTP is an Application layer protocol which means that web-browsers, as clients, are able to make requests to servers. On it's own HTTP is insecure but it has been paired with TLS encryption to make traffic secure, HTTPS (HTTP Secure).</p>

[HTTP Enumeration Basics](https://github.com/jmeliendrez/ejptv2/blob/main/Enumeration/Basics/HTTP%20Enumeration%20Basics.md)

**Further Reading**

- [Wikipedia Article](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)

- [mdn web docs](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)

- [Cloudflare Article](https://www.cloudflare.com/learning/ddos/glossary/hypertext-transfer-protocol-http/)

## SQL
**What is SQL?**
<p>Structure-Query Language (SQL) is a programming language used specifically to create, manage and access databases. It is used in relational database management systems (RDMS) such as MySQL, SQLite, Oracle, though the syntax may differ. It is important to understand SQL on asurface level and how relational databases work so that you can navigate around it.</p>

[SQL Enumeration Basics](https://github.com/jmeliendrez/ejptv2/blob/main/Enumeration/Basics/SQL%20Enumeration%20Basics.md)

**Further Reading**

- [Wikipedia Article](https://en.wikipedia.org/wiki/SQL)

- [w3schools: Introduction to SQL](https://www.w3schools.com/sql/sql_intro.asp)

- [Tutorials Point: Introduction to SQL](https://www.tutorialspoint.com/sql/sql-overview.htm)
