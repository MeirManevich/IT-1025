# Executive Summary #

In this Unit, you will take a break from the exciting realm of programming and creation, to focus on an important foundational topic which should always be at the forefront of any project you work on. Security. You will begin by learning how networks are designed and how they communicate with each other, and then move on to securing the information moving across those networks, to protect your data from prying eyes. This is essential to keeping your users safe.

***

# Lucidchart #

My experience using Lucidchart was smooth and easy. The interface was familiar, quite like word editing programs I've used, and it was almost self-explanatory to get started making a simple chat. It seems like a very useful tool to have for the future!

# Introduction to Networking #
### Data Transmission ###
  * A packet is a fundamental unit of data in a network. Information is split up into packets and then sent to their destination to be reassembled

  * Packet-Switching is what allows the packets to be reassembled into their intended order. Since packets are not always sent chronologically (to increase efficiency of data transmission speeds), packet-switching is necessary to present the user at the destination with a legible piece of information, not a jumbled up mess of data.

  * An IP Address is a unique identification number, used to identify networks and destinations for data to be retrieved from and transmitted to.

  * A DNS is a Domain Name Server, a server which acts as a directory of addresses for other domains. So a network can request the address of a domain from a DNS to connect to that domain.

  * Protocols are rules of communication within a network. When the devices connected to a network all follow the network protocol, communication can happen seamlessly. And the Internet is a protocol for networks with differing protocols to all communicate with each other, allowing all computer systems in the world to be connected. This course being entirely online is one result of that.

### Networking Hardware ###

  * Hubs and switches allow computers to locally connect to each other, creating a network. A hub is quite simple, because all it does is relay any information it receives to all the computers connected to it. This is useful for broad file sharing. Switches are a little more advanced, because they can read addresses attached to information and route data to specific destinations in the network based on those addresses. So you can send data to a single computer on a network with a switch without every other connected device receiving a copy.

  * A router is a device to connect networks with each other, not devices. So if a device in a network sends data to the router with an IP address for another network of devices, the router will route that data along its network of networks to reach its designated network.

### Network Topologies ###

  * The topology of a network is very important to its durability. Older networking topologies like star, ring, and bus topologies all were quite cheap and easy to set up, but suffered from durability issues due to their singular point of failure. If just one part went down in these networks, the whole thing failed. Better and more complicated systems have been developed since, by introducing redundancies to networks, reducing the chances of a network crash.

  * Infrastructure and wireless mesh topologies both have redundancies in place to strengthen their networks. Infrastructure incorporates both wired devices and wireless routers to connect wireless devices all to each other. A wireless mesh connects multiple wireless routers to each other. But both rely on a central switch, which could be a single point of failure, but an infrastructure system seems better to me, since incorporating wired devices ensures packets don't get lost and the connections are stable. In a wireless mesh, with chained wireless connections, it can be easy to have packet loss and an unstable connection.
 
### Network Design ###

  * The network I designed starts with a router in the center of the action, but there are redundancies in place in case the router goes down. The router connects to a wireless router for wireless devices, and it connects to the two computers. The two computers are connected to the printer, and they are connected to each other, directly linking them in case the router fails. This way they can still communicate with each other, regardless of their connection to the router.

### NSA/CSS ###

  * The NSA/CSS is a government project to prevent and fight digital attacks on the US security systems. They invest in research and development and partner with schools to help promote STEM education.

***

# Cybersecurity and Encryption #

### Information Systems Security ###

  * Having a chat online with Amazon involves the security triad. First, confidentiality ensures that none of the information from the chat is available to anyone not authorized to see the messages. Integrity ensures that the messages you are sending and receiving aren’t altered in any way that wasn’t intended by the author. And availability ensures that the chat can happen in real-time, allowing you to converse fluidly.

  * Authentication is necessary in our daily lives. Driving a car requires a license, buying beer, requires proof of age, and using your phone requires a password or facial/fingerprint identification.

  * Access Control is what allows authenticated users to access and manipulate information in a system. An Access Control List (ACL) is a list of every user and the permissions they have for different data in a system. Although this works, it can quickly get out of hand with too many users and data points. So Role-Based Access Control solves this problem by introducing roles, which are assigned to data and users. Only users with roles that correspond with the roles associated with the data they desire can have access. This way access can be granted or revoked to as many people as needed at once by changing the role of the data.

  * A ciphertext is text that has been jumbled up by an encryption method to be unreadable to public eyes. Private keys are used to decrypt the messages, so only those with the keys have access. A public key is something anyone can use to encrypt a message to send but a private key is needed in addition to the public key to decrypt the information

  * This process, called Public Key Cryptography, is very important in this day and age, where we send data to each other all the time without meeting people. We can just agree on a public key, but only with our private keys can we decrypt the information, so anyone trying to intercept our messages will have only half of the full key needed for decryption.


### Cryptography ###

  * Using the Caesar Cipher, the message “hello yes this is a message” became “ifmmp zft uijt jt b nfttbhf” by shifting the dial over one letter, so ‘a’ becomes ‘b’, ‘b’ becomes ‘c’, and so on.

   * The Frequency Fingerprint is interesting. Typing a few random sentences, it became clear that vowels like ‘a’ ‘e’ and ‘i’ and consonants like ‘t’ and ‘s’ are quite frequent. I suppose it makes sense, due to how common those letters are in common English words. I suspect the results would differ, language to language, depending on the composition of the most common words.

  * A Polyalphabetic Cipher is an encryption method which uses multiple Caesar Ciphers together to make a message much more difficult to decrypt. It uses a “shift word” which is converted into numbers based on the numerical position of each letter and then those numbers are repeated for each letter of the message to shift the letter over by that many spaces.

   * Encrypting the message, “An IT course” with the shift word “computer” results in “dc vj xizjvt.” This is obtained by shifting each letter by the number of the shift word letter assigned to it. So the first letter ‘a’ is assigned to ‘c’ which has a value of 3, so it is shifted over by 3 and is encrypted into ‘d.’ Likewise, the next letter, ‘n’ is assigned to the value of ‘o’ which is 15, so it is encrypted to ‘c’ which is 15 letters after ‘n.’ This process is repeated for each letter to obtain the encrypted message, and reversed to decrypt it.

### Brute-Force ###

  * Brute-Force can be used to crack codes from a Caesar Cipher, because after trying enough key possibilities, you will find the right key and decrypt the message. Kerckhoffs’s principle states that even if everything is known about a system except the key, the information is safe. And while that is true, once the system is known, hackers can get started on trying to find the key through brute-force. Since the Caesar Cipher is so well-known, hackers don’t need to figure out your decryption method. They can start working on the key right away. So I think Kerckhoffs’s principle is more applicable to systems with more complex keys, like a Polyalphabetic Cipher or even more complex systems, where the hackers need to first determine how the information is encrypted before they can even get started on trying to find the key.

***
# Conclusion #

As a lover of creativity and visuals, I found using Lucidchart to be my favorite part of this Unit. I recognize how important cybersecurity is, but it doesn’t particularly appeal to me. But using the Khan Academy interactive ciphers was pretty cool. I can see how people can enjoy sending each other encrypted messages and decrypting them by hand for fun. I am glad that there are other people who are interested though, so I can be safe and secure when I am using the internet. I am really looking forward to the next Units, to getting back into programming. I can see we will touch on HTML and some more Python, both of which excite me!
