Currently, the most popular system for sharing files is another peer-to-peer network called Gnutella, or the Gnutella network. There are two main similarities between Gnutella and the old Napster:

Users place the files they want to share on their hard disks and make them available to everyone else for downloading in **peer-to-peer** fashion.
Users run a piece of **Gnutella software** to connect to the Gnutella network.
There are also two big differences between Gnutella and the old Napster:
- There is **no central database** that knows all of the files available on the Gnutella network. Instead, all of the machines on the network tell each other about available files using a distributed query approach.
- There are **many different client applications** available to access the Gnutella network.

Because of both of these features, it would be difficult for a simple court order to shut Gnutella down. The court would have to find a way to block all Gnutella network traffic at the ISP and the backbone levels of the Internet to stop people from sharing.

# Gnutella Clients
![[Pasted image 1.png]]
The original Napster had one piece of "client software" -- the software that users ran on their machines to access the Napster servers. Gnutella has dozens of clients available. Some of the popular Gnutella clients include:
- BearShare
- Gnucleus
- LimeWire
- Morpheus
- WinMX
- XoloX

## How a Gnutella client finds a song
Given that there is no central server to store the names and locations of all the available files, how does the Gnutella software on your machine find a song on someone else's machine? The process goes something like this:
- you type in the name of the song or file you want to find.
- your machine knows of at least one other Gnutella machine somewhere on the network. It knows this becasue you've told it the location of the machine by typing a IP address, or because the software has an IP address for a Gnutella host pre-programmed in. Your machine sends the song name you typed in to the Gnutella machine(s) it knows about.
- These machines seach to see if the request file is on the local hard disk. If so, they send back the file name and IP to the request.
- At the same time, all of these machines send out the same request tothe machine they are connected to, and the process repeats.
- A request ha a TTL linit placed on it. A request might go out 6 or 7 levels deep before it stopes propagating. If each machine on Gnutella network knows of just 4 other, that mean that your request might reach 8.000 or other machines on Gnutelaa network if it progagrates 7 level deep.
It is an extremely simple and clever way of distributing a query to thousands of machines very quickly.
This approach has one big advantage -- **Gnutella works all the time.** As long as you can get to at least one other machine running Gnutella software, you are able to query the network. No court order is going to shut this system down, because there is no one machine that controls everything. However, Gnutella has at least three disadvantages:

There is no guarantee that the file you want is on any of the 8,000 machines you can reach.
Queries for files can take some time to get a complete response. It might be a minute or more before all of the responses, seven levels deep, come in.
Your machine is part of this network. It is answering requests and passing them along, and in the process routing back responses as well. You give up some amount of your bandwidth to handle requests from all the other users.
Apparently, these disadvantages are minor, because people have downloaded hundreds of millions of copies of Gnutella client