---
type: pc
race: "Fiend (demon)"
class:
 - "Fury of Kostchtchie"
subClass:
 - "CR 14"
cover: "Fury of Kostchtchie.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/14
  - source/bgg
---
###### Fury of Kostchtchie
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Fury of Kostchtchie.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 216 (16d12 + 112) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 10 | 25 | 10 | 12 | 11 |
| **Mod** | +8 | +0 | +7 | +0 | +1 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Abyssal, Giant
**Saving Throws:** Con +12, Wis +6
**Skills:** Athletics +13, Perception +6
**Damage Resistances:** fire; lightning; poison
**Damage Immunities:** cold
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Chilling Aura.** A creature that starts its turn within 10 feet of the fury must succeed on a DC 20 Constitution saving throw or take 11 (2d10) cold damage.

**Magic Resistance.** The fury has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The fury makes two Fist or Rock attacks.

**Fist.** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 17 (2d8 + 8) bludgeoning damage plus 10 (3d6) cold damage, or 17 (5d6) cold damage if the target took damage from the fury's Chilling Aura since the end of the fury's last turn.

**Rock.** Ranged Weapon Attack: +13 to hit, range 60/240 ft., one target. *Hit:* 30 (4d10 + 8) bludgeoning damage.


---

### Bonus Actions

**Charge.** The fury can move up to its speed toward an enemy it can see.


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