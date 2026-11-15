TASK 7.1:
-->Concept |Explanation |Example
1. LAN |A network covering a small area. |Home or office network
2. MAN |A network covering a city or large campus area. |City-wide network
3. WAN |A network covering large geographical areas. |Internet
4. DNS |Translates domain names into IP addresses. |Looking up a website domain
5. Router |Connects networks and forwards data. |Home router
6. Protocol |A set of rules used for communication. |HTTP / HTTPS
7. Packet switching |Divides data into packets that travel across a network. |Sending data over the internet
8. Client-server |A client requests a service and a server provides it. |Browser requesting a webpage


TASK 7.2:
-->Connectivity Test Command:
-- ping -c 4 example.com
--> The ping command checks whether a destination can be reached over a network by sending test messages and measuring the responses.
-->The -c 4 option sends four test packets and then stops.
-->This test helps identify whether a destination responds to network requests. It can also display response times and packet loss.

-->DNS Lookup Command:
-- nslookup example.com
--> The nslookup command queries the Domain Name System to find information about a domain name.
--> It can display the DNS server that answered the query and the IP address associated with the requested domain.

--> Role of DNS:
--> DNS acts like an address directory for the Internet. People remember domain names more easily than numerical IP addresses.
-->When a user enters a website name into a browser, DNS helps translate that domain name into an IP address so the browser can locate the appropriate server.


TASK 7.3:
--> The user enters a website address in the browser.

--> The browser checks for the network address associated with the domain.

--> DNS translates the domain name into an IP address.

--> The computer sends a request through its network connection and router.

--> The request reaches the website's server using the required network protocols.

--> The server processes the request and sends a response.

--> The browser receives the response and displays the webpage.


2. Commands Used:
ping	
ping -c 4 example.com	
nslookup	
nslookup example.com	
Terminal	
Web Browser	

3. My Understanding:

A computer network allows devices to communicate and share information. LAN, MAN and WAN describe networks covering different geographical areas.

DNS helps users access websites using domain names instead of remembering numerical IP addresses. Routers forward data between networks, while protocols define the rules devices follow when communicating.

4. Difficulties Faced:

Understanding the differences between LAN, MAN and WAN and learning how DNS translates domain names into IP addresses were the main conceptual challenges.

It was also important to understand the difference between a router, a protocol and packet switching because they perform different roles in networking.

5. How I Resolved Them:

I reviewed the purpose of each networking concept and compared them using practical examples.

I studied the ping command to understand connectivity testing and nslookup to understand how domain names are resolved.

Breaking website communication into individual steps made the overall process easier to understand.

6. Evidence / Files

The following file and activities are associated with this mission:

-- mission-07-networking/README.md — Networking concepts, explanations and observations.
-- Connectivity testing using ping.
-- DNS lookup using nslookup.
-- Explanation of the website communication process.

Any screenshots or copied Terminal output should be privacy-safe. Personal IP addresses, Wi-Fi names, usernames and other identifying network details must not be published.






