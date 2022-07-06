
# ENTREPRISE NETWORK

An enterprise network is the backbone for facilitating a organization’s
communications and connecting computers and devices throughout departments.
An enterprise network environment is usually configured to facilitate access
to data. 
Enterprise networking refers to the physical, virtual and logical design of a network, and how the 
various software, hardware and protocols work together to transmit data.
When it comes to enterprise networking, every organization has different
needs.
# PROJECT DESCRIPTION
An enterprise desires to manage locally a numberof services
depending on the departments. It establishes a network that will allow it to
provide services that:

<li>  Deliver ip addresses to devices that connect to the network. </li>
<li>  Turn domain names into ip addresses (and vise-versa). </li>
<li>  Share files over a tcp/ip network.  </li>
<li>  Allow the user to access web pages through a browser. </li>
<li>  Transfer email over the network. </li>
 <li> Manage directory services and authentication.  </li>

# MAJOR OBJECTIVES:
The task is to build a network divided into twosubnets with:

<li> One dhcp server responsible for delivering addressesto devices
connected on both subnets. </li>
<li> Managing the domain names will be handled by the DNS server. </li>
<li> The FTP server is used to share files in only one subnet (users on the
other subnet are not allowed toaccess this service). </li>
<li> An HTTP server managing two web pages. one is accessible to
all hosts, and one with restrictedaccess (user-password). </li>
<li> A server managing the email exchange in thecompany. </li>
<li> LDAP (lightweight directory access protocol) is used for directory
services and authentication </li>

# STRUCTURE
The structuring of a project consists in
understanding, explaining and formalizing the
different deliverables to be produced as part of the project, then
establishing the list of tasks that will be necessary to achieve these
productions. 
We now know all the actions to be taken to structure aproject. in our structure we
will represent the necessary protocols to create the network of thiscompany (dhcp, dns,
ftp, mail and http, ldap ) those protocols will be carried out in machines under the virtual box software 
each protocol will take its ip address from the 1st subnet
(192.168.1.20)
For the clients we will use two client (windows 7,ubuntu ) to test
our protocols.

![Capture d’écran 2022-07-06 194053](https://user-images.githubusercontent.com/86807424/177625613-4a6eb025-87c7-43c2-ab0c-e812e89c484a.png)



