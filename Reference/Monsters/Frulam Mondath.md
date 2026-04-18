---
type: pc
race: "Humanoid (human)"
class:
 - "Frulam Mondath"
subClass:
 - "CR 2"
cover: "Frulam Mondath.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/hotdq
---
###### Frulam Mondath
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Hoard of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Frulam Mondath.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (chain mail) |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Hoard of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 13 | 11 | 18 | 15 |
| **Mod** | +2 | +0 | +1 | +0 | +4 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common, Draconic, Infernal
**Saving Throws:** Wis +6, Cha +4
**Skills:** Deception +4, History +2, Religion +2

---

### Actions

**Multiattack.** Frulam attacks twice with her halberd.

**Halberd.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 7 (1d10 + 2) slashing damage.


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