---
type: pc
race: "Fey"
class:
 - "Noggle Wild Mage"
subClass:
 - "CR 1"
cover: "Noggle Wild Mage.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/small
  - cr/1
  - source/lfl
---
###### Noggle Wild Mage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: LFL
___

> [!infobox|no-t right]
> ![[Noggle Wild Mage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Fey |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 22 (4d6 + 8) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | LFL |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 14 | 10 | 12 | 17 |
| **Mod** | +0 | +3 | +2 | +0 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 11
**Languages:** Common, Sylvan
**Saving Throws:** Con +4, Cha +5

---

### Traits

**Bloodied Wild Magic.** While Bloodied, the noggle has a Fly Speed of 30 feet and it can choose for any damage it deals to be Force damage.


---

### Actions

**Multiattack.** The noggle makes two attacks, using Noggling Stick or Befuddling Ray in any combination.

**Noggling Stick.** m +5, reach 5 ft. *Hit:* 5 (1d4 + 3) Bludgeoning damage plus 2 (1d4) Psychic damage.

**Befuddling Ray.** r +5, range 60 ft. *Hit:* 6 (1d6 + 3) Psychic damage, and the target subtracts 1d4 from the next saving throw it makes before the end of the noggle's next turn.


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