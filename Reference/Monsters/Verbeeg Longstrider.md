---
type: pc
race: "Giant"
class:
 - "Verbeeg Longstrider"
subClass:
 - "CR 5"
cover: "Verbeeg Longstrider.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/large
  - cr/5
  - source/idrotf
---
###### Verbeeg Longstrider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Verbeeg Longstrider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Giant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 (hide armor) |
> | :FasHeart: HP | 119 (14d10 + 42) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 15 | 16 | 13 | 14 | 10 |
| **Mod** | +4 | +2 | +3 | +1 | +2 | +0 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Giant
**Saving Throws:** Dex +5, Con +6, Wis +5
**Skills:** Animal Handling +5, Athletics +7, Stealth +5

---

### Traits

**Simple Weapon Wielder.** A simple weapon deals one extra die of its damage when the verbeeg hits with it (included in the attack).


---

### Actions

**Multiattack.** The verbeeg makes two melee attacks.

**Spear.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 14 (3d6 + 4) piercing damage, or 17 (3d8 + 4) piercing damage if used to make a ranged attack or used with two hands to make a melee attack.

**Sling.** Ranged Weapon Attack: +5 to hit, range 30/120 ft., one target. *Hit:* 9 (3d4 + 2) bludgeoning damage. If the target is a creature, it must succeed on a DC 15 Constitution saving throw or be stunned until the end of its next turn.


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