---
type: pc
race: "Undead"
class:
 - "Vampire Nightbringer"
subClass:
 - "CR 8"
cover: "Vampire Nightbringer.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/small
  - cr/8
  - source/xmm
---
###### Vampire Nightbringer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Vampire Nightbringer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Small Undead |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 142 (19d8 + 57) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 18 | 16 | 13 | 14 | 15 |
| **Mod** | +3 | +4 | +3 | +1 | +2 | +2 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 15
**Languages:** Common plus one other language
**Saving Throws:** Dex +7, Wis +5
**Skills:** Perception +5, Stealth +7
**Damage Immunities:** cold; necrotic
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Sunlight Hypersensitivity.** The vampire takes 10 Radiant damage if it starts its turn in sunlight. While in sunlight, it has Disadvantage on attack rolls and ability checks.


---

### Actions

**Multiattack.** The vampire makes one Bite attack and one Shadow Strike attack.

**Bite.** m +7, reach 5 ft. *Hit:* 7 (1d6 + 4) Piercing damage plus 10 (3d6) Necrotic damage. The target's Hit Point maximum decreases by an amount equal to the Necrotic damage taken, and the vampire regains Hit Points equal to that amount.

**Shadow Strike.** m +7, reach 5 ft. *Hit:* 7 (1d6 + 4) Slashing damage plus 14 (4d6) Cold damage.


---

### Bonus Actions

**Shadow Stealth.** While in Dim Light or Darkness, the vampire takes the Hide action.


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