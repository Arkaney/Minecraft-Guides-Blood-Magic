---
title: Teleposer
media_order: Teleposer.jpg
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

The Teleposer is a block that will act just like a teleporter but with the only limitation being that you need to apply a redstone signal and it needs to be linked to another Teleposer.

You will need to craft a few Teleposition Focus first, this can be done by placing an Ender Pearl into the Tier 4 Blood Altar with 2,000 LP. This can then be crafted together with gold and more ender pearls to make a Teleposer, you will need 2 of these for this to work.

Place down the first Teleposer, this will act as the primary Teleposer, this means once this is set up this block (the first one) will be given a redstone signal to send whatever block you have above it to the next Teleposer:

![](Teleposer.jpg)

Place down your second Teleposer wherever you want to teleport the block (a chest in this case). Next you will need to use a Teleposition focus to bind the Teleposers. With the Teleposition focus in hand right click the first block and then do the same with the second block, once done right click the first Teleposer with an empty hand and place in the Teleposition focus.

![](Teleposer%20example.jpg)

With the Teleposition focus you will only be able to teleport 1 block above the Teleposer, this can be upgraded to a 3x3, with the Enhanced Teleposition focus and 5x5 with the Reinforced Teleposition focus.

Teleposers don’t have a range limit or a dimension limit, this does mean they can be used to transport blocks back to base that normally can not be picked. By default Spawners and Bedrock are turned off in the configs. To disable this you will need to edit the Blood Magic config file:

```js
blacklist {
    # Stops listed blocks and entities from being teleposed.
    # Use the registry name of the block or entity. Vanilla objects do not require the modid.
    # If a block is specified, you can list the variants to only blacklist a given state.
    S:teleposer <
        bedrock
        mob_spawner
     >
```

