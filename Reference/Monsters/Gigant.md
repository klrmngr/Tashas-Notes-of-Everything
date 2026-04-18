---
type: pc
race: "Monstrosity"
class:
 - "Gigant"
subClass:
 - "CR 20"
cover: "Gigant.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/20
  - source/bgg
---
###### Gigant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Gigant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 325 (21d20 + 105) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 14 | 21 | 3 | 14 | 11 |
| **Mod** | +7 | +2 | +5 | -4 | +2 | +0 |

**Speed:** 50 ft., burrow 50 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 18
**Languages:** —
**Saving Throws:** Dex +8, Wis +8
**Skills:** Perception +8

---

### Traits

**Spell-Resistant Carapace.** The gigant has advantage on saving throws against spells, and any creature that makes a spell attack against the gigant has disadvantage on the attack roll.


---

### Actions

**Multiattack.** The gigant makes one Mandibles attack and two Talons attacks.

**Mandibles.** Melee Weapon Attack: +13 to hit, reach 10 ft., one creature. *Hit:* 21 (4d6 + 7) slashing damage, and the target has the grappled condition (escape DC 17). Until the grapple ends, the target takes 21 (4d6 + 7) slashing damage at the start of each of the gigant's turns. While the gigant is grappling a target, it can't use Mandibles against other targets.

**Talons.** Melee Weapon Attack: +13 to hit, reach 20 ft., one target. *Hit:* 17 (3d6 + 7) slashing damage, and the target is pulled 10 feet straight toward the gigant.

**Scale Dust (Recharge 5–6).** The gigant releases magical dust from its wings in a 30-foot cube. Each creature in that area must make a DC 19 Constitution saving throw, taking 45 (10d8) poison damage on a failed save, or half as much damage on a successful one. On a success or failure, the creature has the poisoned condition for 1 hour. While poisoned this way, the creature can't regain hit points.


---

### Bonus Actions

**Drone.** The gigant produces a horrid droning sound by rapidly beating its wings. Each creature within 10 feet of the gigant must succeed on a DC 19 Constitution saving throw or take 10 (3d6) thunder damage and have the incapacitated condition until the end of its next turn. The gigant can then fly up to half its flying speed.


---

> [!column|flex 3]
>> [!important]- QUESTS:
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Name
>>     filters:
>>       and:
>>         - file.inFolder("Compendium/Party/Quests")
>>         - file.hasLink(this.file)
>>     order:
>>       - file.name
>> ```
>
>> [!note]- HISTORY
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Session Notes
>>     filters:
>>       and:
>>         - file.inFolder("Session Notes")
>>         - file.hasLink(this.file)
>> ```