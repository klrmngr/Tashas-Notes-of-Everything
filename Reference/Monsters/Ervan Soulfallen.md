---
type: pc
race: "Humanoid (human)"
class:
 - "Ervan Soulfallen"
subClass:
 - "CR 5"
cover: "Ervan Soulfallen.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/lrdt
---
###### Ervan Soulfallen
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: LRDT
___

> [!infobox|no-t right]
> ![[Ervan Soulfallen.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 84 (13d8 + 26) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | LRDT |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 14 | 11 | 8 | 17 |
| **Mod** | +0 | +2 | +2 | +0 | -1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 9
**Languages:** Common, Draconic
**Skills:** Arcana 3, Deception +6

---

### Actions

**Multiattack.** Ervan uses his staff to make three Arcane Blast attacks.

**Arcane Blast.** Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 13 (3d6 + 3) force damage.

**Acid Rain (Recharges after a Short or Long Rest).** Acid falls in a 10-foot-radius, 20-foot-high cylinder centered on a point Ervan can see within 120 feet of himself. Each creature in that area must make a DC 14 Dexterity saving throw, taking 22 (4d10) acid damage on a failed save, or half as much damage on a successful one.


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