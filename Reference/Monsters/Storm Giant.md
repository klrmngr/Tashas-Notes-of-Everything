---
type: pc
race: "Giant"
class:
 - "Storm Giant"
subClass:
 - "CR 13"
cover: "Storm Giant.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/13
  - source/mm
---
###### Storm Giant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Storm Giant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 16 (scale mail) |
> | :FasHeart: HP | 230 (20d12 + 100) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 14 | 20 | 16 | 18 | 18 |
| **Mod** | +9 | +2 | +5 | +3 | +4 | +4 |

**Speed:** 50 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 19
**Languages:** Common, Giant
**Saving Throws:** Str +14, Con +10, Wis +9, Cha +9
**Skills:** Arcana +8, Athletics +14, History +8, Perception +9
**Damage Resistances:** cold
**Damage Immunities:** lightning; thunder

---

### Traits

**Amphibious.** The giant can breathe air and water.


---

### Actions

**Multiattack.** The giant makes two greatsword attacks.

**Greatsword.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 30 (6d6 + 9) slashing damage.

**Rock.** Ranged Weapon Attack: +14 to hit, range 60/240 ft., one target. *Hit:* 35 (4d12 + 9) bludgeoning damage.

**Lightning Strike (Recharge 5–6).** The giant hurls a magical lightning bolt at a point it can see within 500 feet of it. Each creature within 10 feet of that point must make a DC 17 Dexterity saving throw, taking 54 (12d8) lightning damage on a failed save, or half as much damage on a successful one.


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