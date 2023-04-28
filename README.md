# 198

Revise the common concepts of Python
Understand about ports in software development

High speed ethernet works on which type of cable?
Ans:Optical Fibre
----------------
File Transfer protocol (FTP) is built on which architecture:
ans:Client-Server
---------------
PYTHON & PORTS
——————————
You see how the browser automatically inserted an “https://” before the URL?

It happens because WhitehatJr’s web server is an HTTPS server which means secure server , and it's fetching all the incoming connections on a particular port address i.e whitehatjr.com in our case.

It means as soon as we enter “whitehatjr.com” in our browser, the HTTPS server running in the backend will detect our incoming request and in response send the HTML content of the website through a port on your browser.HTTP generally use Transmission Control Protocol (TCP) connections to communicate through port


TCP is a Transmission Control Protocol which is used to build a connection between the source computer and the destination one on the network.For devices to communicate via TCP, they use TCP ports. Every port assigned with a unique number .Every port has unique number based on different different applications:
——————————————————————
Let’s understand this with an example. Suppose you’ve opened 2 different applications on your device One is Email application and second one is video game.

Now the Email application and Video game application can be transferring data to the server at the same time and it's happening simultaneously.r,In order to differentiate between ports based on applications different unique numbers are assigned to these applications. Therefore we have number of ports available in the network
———————————————————————————————
That’s where IP Addresses come into play. A port number is always used along with an IP address.

That’s where IP Addresses come into play. A port number is always used along with an IP address.
It means if two same applications will be on the same port but their IP address varies, which makes their combination unique, they can run simultaneously.

A TCP port is a 16 bit unsigned value. This means that there can only be a finite number of TCP ports available in the world.
Bit is a Binary digits that can hold only one of two values: 0 or 1.

that’s why we have specifically 65,535 ports available in the world.


Now out of these 65,535 ports, only the first 1,024 ports are well known ports majorly agreed upon in the world of technology for specific applications For example, the well known port of HTTP is 80. Similarly, port 443 is well known for HTTPS and it used to transfer data securely.

————————————————————————

Port No Process Name Description Application
20/21 FTP File Transfer Protocol Data Transfer\
23 SMTP Simple Mail Transport Protocol Email Routing \
80 HTTP HyperText Transfer Protocol Used to transfer hypertext such as web pages and share data \
443 HTTPs HyperText Transfer Protocol Secure Extension of HTTP Protocol, used for secure communication over Protocol \
53 DNS Domain Name Server Used to establish connection between web servers and web sites \
22 SSH Secure Shell Enables two computers to communicate 123 NTP Network Time Protocol Used for synchronizing multiple networks \
23 Telnet Telnet Used for Server-Client Program \
110 POP3 Post Office Protocol Help you to download message/email from you inbox to Local Computer\
——————————————————

● Open a CMD prompt 
● Type in the command: netstat

Ports other than 1024 i.e in the range 1024 to 49151 are reserved for future ports. And if you look at ports above in the range i.e 49152 to 65535 they are unofficially used by different technologies.

————————————————

Remember how our Flask server always runs on port 5000 by default?

Look closely at the last line. It says that it’s running on 127.0.0.1:5000. Here, 127.0.0.1 is the IP Address and 5000 is the port number. They are separated by a :

——————
If we run another Flask server while our first one is running, we get -
it gives an error which says that Address is already in use This is because our second Flask App is again trying to run on IP address 127.0.0.1 and on port number 5000. This combination of IP Address and Port is already in use, therefore it says that the address is already in use.

————————

 all computers/ websites/servers have a local ip address but we remember domain names like google.com, whitehatjr.com, amazon. com.Actually in backend domain names are usually mapped with IP Addresses of the server because it's easy -to remember domain names since they are easier to remember as compared to complex IP addresses. So people usually access websites with domain names.

—————————

When we combine IP addresses and ports together it becomes a socket.


When we enter any website, let’s say “https://www.whitehatjr.com”, we are simply just connecting with the IP Address or domain name that whitehatjr.com and it is mapped to port i.e https means that we are connecting with it through port 443.

———————————————————————

data types python has?
● Integers ● Strings ● Booleans ● None ● Float
—————————
today  Input ● Variables ● Data Types
Lists are array-like data structures in Python that can hold any number of values regardless of their data types. The elements are separated with a comma (,) and are placed within square brackets [].

all elements in array have index value The first element of a list has index 0. The second element has an index 1. Third element has an index 2. and so on. Now what would be the index of the 8th element in the list?

——————————————

1. len(list) to find the length of the lists.

 2. list.append(element) to add an element to the lists.

———————————————————

Dictionaries are similar to Objects in Python. They have key and value pairs that can hold information for us.

We had covered a lot of other concepts too, such as functions, loops, if else statements, etc.
----------------------------
 print the first 10 odd numbers using a while loop in Python. 

——————————————
 create a function which takes a dictionary and prints 2 lists. First list would contain all the keys and the second would contain all the values.

---------------------------------------




