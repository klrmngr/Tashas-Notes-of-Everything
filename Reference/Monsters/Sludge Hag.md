---
type: pc
race: "Fey"
class:
 - "Sludge Hag"
subClass:
 - "CR 3"
cover: "Sludge Hag.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/3
  - source/mgelft
---
###### Sludge Hag
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MGELFT
___

> [!infobox|no-t right]
> ![[Sludge Hag.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 82 (11d8 + 33) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | MGELFT |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 16 | 13 | 14 | 14 |
| **Mod** | +4 | +1 | +3 | +1 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common, Draconic, Sylvan
**Skills:** Arcana +3, Deception +4, Perception +4, Stealth +3

---

### Traits

**Amorphous.** The sludge hag can move through a space as narrow as 1 inch wide without squeezing.

**Amphibious.** The sludge hag can breathe air and water.


---

### Actions

**False Appearance.** The sludge hag collapses into a oily pool of sludge. While motionless, the sludge hag is indistinguishable from any other oily pool of oozy drippiness.

**Sludge Slap.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 12 (1d8 + 8) bludgeoning damage, plus 4 (1d8) acid damage. Sludge Slap does both bludgeoning and acid damage.


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