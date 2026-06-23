##  Peer-to-Peer (P2P) Architecture
- Peer-to-peer network also known as point-to-point network in which all the computers are directly linked together with equal privileges and responsibilites for sharing the data.  
- In a P2P system, every node has an equal role to play and the same functionalities, which means that the loads are well shared.   
- There is no server in it.

    ![p2p](/Images/P2P.png)

## Types of P2P Networks

1. **Unstructured P2P Networks**     
In this model, nodes connect randomly, forming a network with no specific organization or structure.
    - **How it works**: Resources are located by sending queries across the network until the desired file or node is found.
    - **Pros**: Highly adaptable; nodes can easily join or leave without disrupting the system.
    - **Cons**: Searching for content can be inefficient and consume high bandwidth
    - **Examples**: Early file-sharing protocols like Gnutella and original Napster.

2. **Structured P2P Networks**  
These networks use strict, algorithm-based rules (such as Distributed Hash Tables or DHTs) to organize nodes.

    - **How it works**: Each node is assigned specific responsibilities for a portion of the network's data, allowing queries to be routed directly to the correct node.
    - **Pros**: Highly efficient searching and data retrieval, even for rare files.
    - **Cons**: More difficult to set up and maintain.
    - **Examples**: BitTorrent and IPFS.

3. **Hybrid P2P Networks**      
Hybrid networks combine the direct node-to-node communication of P2P with a centralized server.

    - How it works: A central server indexes the files or locations of peers, while the actual data transfer happens directly between the peers themselves.
    - Pros: Fast and accurate searching, as the central index easily points you to where the data is stored.
    - Cons: The central server acts as a single point of failure; if it goes down, the search function breaks.
    - Examples: Early versions of Spotify or direct messaging apps that use a server for user discovery.

## Advantages of P2P Network
- **Easy to Maintain**: The network is easy to maintain because each node is independent of the other.
- **Less Costly**: Since each node acts as a server, therefore the cost of the central server is saved. Thus, there is no need to buy an expensive server.
- **No Network Manager**: In a P2P network since each node manages his or her own computer, thus there is no need for a network manager.
- **Adding Nodes is Easy**: Adding, deleting, and repairing nodes in this network is easy.
- **Less Network Traffic**: In a P2P network, there is less network traffic than in a client/ server network.

## Disadvantages of P2P Network
- **Data is Vulnerable**: Because of no central server, data is always vulnerable to getting lost because of no backup.
- **Less Secure**: It becomes difficult to secure the complete network because each node is independent. 
- **Slow Performance**: In a P2P network, each computer is accessed by other computers in the network which slows down the performance of the user.
- **Files Hard to Locate**: In a P2P network, the files are not centrally stored, rather they are stored on individual computers which makes it difficult to locate the files.