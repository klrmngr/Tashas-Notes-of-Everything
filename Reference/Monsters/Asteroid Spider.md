---
type: pc
race: "Monstrosity"
class:
 - "Asteroid Spider"
subClass:
 - "CR 15"
cover: "Asteroid Spider.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/15
  - source/mcv1sc
---
###### Asteroid Spider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV1SC
___

> [!infobox|no-t right]
> ![[Asteroid Spider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 348 (24d20 + 96) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | MCV1SC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 10 | 18 | 17 | 13 | 12 |
| **Mod** | +8 | +0 | +4 | +3 | +1 | +1 |

**Speed:** 60 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 120 ft. while the spider's eyes are closed, darkvision 120 ft., passive Perception 21
**Languages:** —
**Saving Throws:** Con +9, Wis +6
**Skills:** Perception +11, Stealth +5

---

### Traits

**False Appearance.** If the spider is motionless, has its eyes and mouth closed, and has its legs wrapped around its body at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the spider move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the spider is anything other than an asteroid.

**Legendary Resistance (3/Day).** If the spider fails a saving throw, it can choose to succeed instead.

**Unusual Nature.** The spider doesn't require air.


---

### Actions

**Multiattack.** The spider makes two Web Strand attacks, uses Reel, and makes two Bite attacks.

**Bite.** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 21 (3d8 + 8) piercing damage plus 10 (3d6) acid damage.

**Web Strand.** Ranged Weapon Attack: +13 to hit, reach 120 ft., one creature. *Hit:* The target is grappled (escape DC 18). The web strand can be attacked and destroyed (AC 12; 20 hit points; vulnerability to fire damage; immunity to bludgeoning, poison, and psychic damage). The spider can grapple up to six creatures at a time using its web strands.

**Reel.** The spider pulls each creature grappled by it up to 60 feet straight toward itself.


---

### Bonus Actions

**Snare Ship (1/Day).** The spider weaves a magical web around a spelljamming ship it can see within 120 feet of itself. The web lasts for 1 minute and suppresses the magic of any spelljamming helm aboard the ship. Decks and other surfaces of the ship that aren't enclosed become difficult terrain until the effect ends. The web is impervious to damage but is destroyed by a successful casting of dispel magic (DC 18).


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