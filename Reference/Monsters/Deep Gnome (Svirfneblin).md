---
type: pc
race: "Humanoid (gnome)"
class:
 - "Deep Gnome (Svirfneblin)"
subClass:
 - "CR 1/2"
cover: "Deep Gnome (Svirfneblin).png"
campaign:
locations:
tags:
  - race/gnome
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-2
  - source/mm
---
###### Deep Gnome (Svirfneblin)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Deep Gnome (Svirfneblin).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Humanoid (gnome) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 15 (chain shirt) |
> | :FasHeart: HP | 16 (3d6 + 6) |
> | :FasUserGroup: Race | Humanoid (gnome) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 14 | 12 | 10 | 9 |
| **Mod** | +2 | +2 | +2 | +1 | +0 | -1 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** Gnomish, Terran, Undercommon
**Skills:** Investigation +3, Perception +2, Stealth +4

---

### Traits

**Stone Camouflage.** The gnome has advantage on Dexterity (Stealth) checks made to hide in rocky terrain.

**Gnome Cunning.** The gnome has advantage on Intelligence, Wisdom, and Charisma saving throws against magic.


---

### Actions

**War Pick.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.

**Poisoned Dart.** Ranged Weapon Attack: +4 to hit, range 30/120 ft., one creature. *Hit:* 4 (1d4 + 2) piercing damage, and the target must succeed on a DC 12 Constitution saving throw or be poisoned for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success


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