---
type: pc
race: "Giant"
class:
 - "Fire Giant Dreadnought"
subClass:
 - "CR 14"
cover: "Fire Giant Dreadnought.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/14
  - source/mpmm
---
###### Fire Giant Dreadnought
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Fire Giant Dreadnought.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 21 (plate, Dual Shields) |
> | :FasHeart: HP | 187 (15d12 + 90) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 9 | 23 | 8 | 10 | 11 |
| **Mod** | +8 | -1 | +6 | -1 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Giant
**Saving Throws:** Dex +4, Con +11, Cha +5
**Skills:** Athletics +13, Perception +5
**Damage Immunities:** fire

---

### Traits

**Dual Shields.** The giant carries two shields, which together give the giant +3 to its AC (accounted for above).


---

### Actions

**Multiattack.** The giant makes two Fireshield or Rock attacks.

**Fireshield.** Melee Weapon Attack: +13 to hit, reach 5 ft., one target. *Hit:* 22 (4d6 + 8) bludgeoning damage plus 7 (2d6) fire damage plus 7 (2d6) piercing damage.

**Rock.** Ranged Weapon Attack: +13 to hit, range 60/240 ft., one target. *Hit:* 30 (4d10 + 8) bludgeoning damage.

**Shield Charge (Recharge 5–6).** The giant moves up to 30 feet in a straight line and can move through the space of any creature smaller than Huge. The first time it enters a creature's space during this move, that creature must succeed on a DC 21 Strength saving throw or take 36 (8d6 + 8) bludgeoning damage plus 14 (4d6) fire damage and be pushed up to 30 feet and knocked prone.


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