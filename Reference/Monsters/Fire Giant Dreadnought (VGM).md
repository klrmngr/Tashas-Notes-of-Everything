---
type: pc
race: "Giant (fire giant)"
class:
 - "Fire Giant Dreadnought"
subClass:
 - "CR 14"
cover: "Fire Giant Dreadnought.png"
campaign:
locations:
tags:
  - race/fire giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/14
  - source/vgm
---
###### Fire Giant Dreadnought
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Fire Giant Dreadnought.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Huge Giant (fire giant) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 21 (plate armor, shields) |
> | :FasHeart: HP | 187 (15d12 + 90) |
> | :FasUserGroup: Race | Giant (fire giant) |
> | :FasBook: Source | Volo's Guide to Monsters |

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

**Dual Shields.** The giant carries two shields, each of which is accounted for in the giant's AC. The giant must stow or drop one of its shields to hurl rocks.


---

### Actions

**Multiattack.** The giant makes two fireshield attacks.

**Fireshield.** Melee Weapon Attack: +13 to hit, reach 5 ft., one target. *Hit:* 22 (4d6 + 8) bludgeoning damage plus 7 (2d6) fire damage plus 7 (2d6) piercing damage.

**Rock.** Ranged Weapon Attack: +13 to hit, range 60/240 ft., one target. *Hit:* 30 (4d10 + 8) bludgeoning damage.

**Shield Charge.** The giant moves up to 30 feet in a straight line and can move through the space of any creature smaller than Huge. The first time it enters a creature's space during this move, it makes a fireshield attack against that creature. If the attack hits, the target must also succeed on a DC 21 Strength saving throw or be pushed ahead of the giant for the rest of this move. If a creature fails the save by 5 or more, it is also knocked prone and takes 18 (3d6 + 8) bludgeoning damage, or 29 (6d6 + 8) bludgeoning damage if it was already prone.


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