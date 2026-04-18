---
type: pc
race: "Construct"
class:
 - "Clapperclaw the Scarecrow"
subClass:
 - "CR 1/2"
cover: "Clapperclaw the Scarecrow.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/small
  - cr/1-2
  - source/wbtw
---
###### Clapperclaw the Scarecrow
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Clapperclaw the Scarecrow.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Construct |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 14 (4d6) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 13 | 11 | 7 | 10 | 10 |
| **Mod** | +2 | +1 | +0 | -2 | +0 | +0 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Sylvan
**Skills:** Stealth +3, Survival +2
**Damage Vulnerabilities:** fire
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned; unconscious

---

### Traits

**Unusual Nature.** Clapperclaw doesn't require air, food, drink, or sleep.


---

### Actions

**Claws.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (2d4 + 2) slashing damage.

**Stuffing.** Clapperclaw stuffs straw or other dead plant matter into itself and regains 2d4 + 2 hit points. Roll a d6; on a 1 or 2, Clapperclaw runs out of stuffing and must spend 8 hours foraging for more before it can use this action again.


---

### Bonus Actions

**Unsettling Presence (Recharge 6).** Clapperclaw targets one creature it can see within 15 feet of it. The target must succeed on a DC 11 Wisdom saving throw or be magically frightened until the end of Clapperclaw's next turn.


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