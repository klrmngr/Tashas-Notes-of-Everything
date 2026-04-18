---
type: pc
race: "Humanoid (thri-kreen)"
class:
 - "Thri-kreen"
subClass:
 - "CR 1"
cover: "Thri-kreen.png"
campaign:
locations:
tags:
  - race/thri-kreen
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/mm
---
###### Thri-kreen
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Thri-kreen.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (thri-kreen) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid (thri-kreen) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 15 | 13 | 8 | 12 | 7 |
| **Mod** | +1 | +2 | +1 | -1 | +1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Thri-kreen
**Skills:** Perception +3, Stealth +4, Survival +3

---

### Traits

**Chameleon Carapace.** The thri-kreen can change the color of its carapace to match the color and texture of its surroundings. As a result, it has advantage on Dexterity (Stealth) checks made to hide.

**Standing Leap.** The thri-kreen's long jump is up to 30 feet and its high jump is up to 15 feet, with or without a running start.


---

### Actions

**Multiattack.** The thri-kreen makes two attacks: one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +3 to hit, reach 5 ft., one creature. *Hit:* 4 (1d6 + 1) piercing damage, and the target must succeed on a DC 11 Constitution saving throw or be poisoned for 1 minute. If the saving throw fails by 5 or more, the target is also paralyzed while poisoned in this way. The poisoned target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Claws.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 6 (2d4 + 1) slashing damage.


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