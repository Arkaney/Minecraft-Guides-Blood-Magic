---
title: 'Ritual of the Green Grove​'
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

**Activation Cost**: 1,000LP  
Very similar to the sigil, the ritual will look at the 3x3 area two blocks above itself and attempt to grow each block with a 30% success rate every second

Using the ritual tinker the ritual can be increased to handle up to 81 crops in a 5 block radius of the Master Ritual Stone (but in the current version, you can’t define a new “Growth” area). This ritual can also be set to consume different types of Will:

| Type of Will     | Effect on Ritual |
|------------------|------------------|
| Raw Will         | This will perform all operations at an accelerated rate, consuming 0.05 Will per successful growth and increasing its speed relative to how much Will is in the Aura |
| Steadfast Will   | This allows you to set an area around the ritual that will be automatically tilled and hydrated. Additionally, any seed that is within this range will be planted on a nearby block if possible. This costs a small amount of Steadfast Will, and its effects do not scale with Will in the Aura | 
| Destructive Will | This will increase the effective maximum range of the ritual, meaning the more Will you have the more crops/plants a single ritual can handle. Thankfully, the ritual does not drain any Destructive Will, however if your Will drops and the ritual's maximum range is lower than what you set it at, the ritual will not work at all until fixed |
| Corrosive Will   | This may shift the fundamental nature of the ritual. When supplied and the new range is properly set, any mobs that enter in the ritual's area of influence will have the "Leech" effect applied. Every few ticks, the plants near the mobs will be damaged and the mob will be damaged proportionally. Fertilizing with mobs directly can prove beneficial! Every 10 seconds that the debuff is applied per mob, 0.2 Corrosive Will will be consumed |
| Vengeful Will    | This will consume 0.05 Will per successful growth and will increase the chance that a given operational tick will be successful on the plant. By default without Will, it is 30%, but for instance if you have 100 Vengeful Will the rate will increase to 80% |