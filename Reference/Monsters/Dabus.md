---
type: pc
race: "Celestial"
class:
 - "Dabus"
subClass:
 - "CR 2"
cover: "Dabus.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/2
  - source/mpp
---
###### Dabus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Dabus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 12 | 16 | 15 | 14 |
| **Mod** | -1 | +2 | +1 | +3 | +2 | +2 |

**Speed:** 20 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** understands all languages but can't speak; communicates via Symbol Speech
**Saving Throws:** Int +5, Wis +4
**Skills:** Insight +4, Perception +6
**Condition Immunities:** exhaustion

---

### Traits

**Physical Restraint.** The dabus doesn't make melee attacks or opportunity attacks, even in self-defense.

**Symbol Speech.** A dabus communicates by creating illusory symbols and pictures that float in the air in front of itself and disappear a few seconds later. A creature that can see such a message can decipher it with a successful DC 10 Intelligence (Investigation) check (no action required).


---

### Actions

**Multiattack.** The dabus makes two Flying Brick attacks.

**Flying Brick.** Ranged Spell Attack: +5 to hit, range 90 ft., one target. *Hit:* 7 (1d8 + 3) bludgeoning damage.

**Grasping Ground (Recharge 6).** The dabus causes a 20-foot-square area of ground it can see within 60 feet of itself to sprout clutching appendages made of stone. Each creature of the dabus's choice in that area must succeed on a DC 13 Dexterity saving throw or take 9 (2d8) bludgeoning damage and have the grappled condition (escape DC 13). While grappled in this way, the creature has the restrained condition. The appendages vanish after 1 minute or if the dabus's concentration ends (as if concentrating on a spell).


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