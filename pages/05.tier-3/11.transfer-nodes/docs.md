---
title: 'Transfer Nodes'
taxonomy:
    category:
        - docs
twittercardoptions: summary
articleenabled: false
musiceventenabled: false
orgaenabled: false
orga:
    ratingValue: 2.5
orgaratingenabled: false
eventenabled: false
personenabled: false
restaurantenabled: false
restaurant:
    acceptsReservations: 'yes'
    priceRange: $
---

Blood Magic has its very own item routing system. This system is no match to an Applied Energistics network or a Storage Drawer system, but it doesn't need to be, it's simple and it works. Before jumping into item routing you need to understand the concept of each system.

Each system has a “Brain” (Master Routing Node) the brain talks to each node and ensures they are all communicating. These brains can only reach so far. Each brain can act as a separate system. In order to set these systems up you will also need a Node Router, this will act as your “wrench” and help configure each network.

When setting up an item routing system you will need to pull items into the system (Input Routing Node) so that it can output (output Routing Node) the items back into another location. Each system will also need a Brain (Master Routing Node).

### How things work

To connect Nodes together you need to right-click the Master routing node and then any input/output node you wish to connect to the network. Once linked successfully you will get a message and a white line that connects to the 2 nodes you have connected:

