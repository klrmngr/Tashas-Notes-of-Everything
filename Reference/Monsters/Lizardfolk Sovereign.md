---
type: pc
race: "Elemental"
class:
 - "Lizardfolk Sovereign"
subClass:
 - "CR 4"
cover: "Lizardfolk Sovereign.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/4
  - source/xmm
---
###### Lizardfolk Sovereign
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Lizardfolk Sovereign.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 12 | 15 | 11 | 11 | 15 |
| **Mod** | +3 | +1 | +2 | +0 | +0 | +2 |

**Speed:** 30 ft., burrow 20 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 14
**Languages:** Draconic, Primordial (Terran)
**Saving Throws:** Con +4, Wis +2
**Skills:** Perception +4, Stealth +5
**Condition Immunities:** frightened

---

### Actions

**Multiattack.** The lizardfolk makes one Bite attack and one Earthen Maul attack.

**Bite.** m +5, reach 5 ft. *Hit:* 8 (1d10 + 3) Piercing damage. If the target is a creature that isn't a Construct or an Undead, the lizardfolk gains Temporary Hit Points equal to the damage dealt.

**Earthen Maul.** m +5, reach 5 ft. *Hit:* 10 (2d6 + 3) Bludgeoning damage. If the target is a Medium or smaller creature, it has the Prone condition.


---

### Bonus Actions

**Charge.** The lizardfolk moves up to its Speed or Swim Speed straight toward an enemy it can see.


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