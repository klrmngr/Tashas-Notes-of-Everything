---
type: pc
race: "Humanoid (any race)"
class:
 - "Blackguard"
subClass:
 - "CR 8"
cover: "Blackguard.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/vgm
---
###### Blackguard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Blackguard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral Chaotic Evil |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 153 (18d8 + 72) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 18 | 11 | 14 | 15 |
| **Mod** | +4 | +0 | +4 | +0 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** any one language (usually Common)
**Saving Throws:** Wis +5, Cha +5
**Skills:** Athletics +7, Deception +5, Intimidation +5

---

### Actions

**Multiattack.** The blackguard makes three attacks with its glaive or its shortbow.

**Glaive.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 9 (1d10 + 4) slashing damage.

**Shortbow.** Ranged Weapon Attack: +3 to hit, range 80/320 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.

**Dreadful Aspect (Recharges after a Short or Long Rest).** The blackguard exudes magical menace. Each enemy within 30 feet of the blackguard must succeed on a DC 13 Wisdom saving throw or be frightened for 1 minute. If a frightened target ends its turn more than 30 feet away from the blackguard, the target can repeat the saving throw, ending the effect on itself on a success.


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