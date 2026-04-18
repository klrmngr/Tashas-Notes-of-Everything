---
type: pc
race: "Fiend (demon)"
class:
 - "Shadow Demon"
subClass:
 - "CR 4"
cover: "Shadow Demon.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/4
  - source/mm
---
###### Shadow Demon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Shadow Demon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Fiend (demon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 17 | 12 | 14 | 13 | 14 |
| **Mod** | -5 | +3 | +1 | +2 | +1 | +2 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Abyssal, telepathy 120 ft.
**Saving Throws:** Dex +5, Cha +4
**Skills:** Stealth +7
**Damage Vulnerabilities:** radiant
**Damage Resistances:** acid; fire; necrotic; thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** cold; lightning; poison
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Incorporeal Movement.** The demon can move through other creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Light Sensitivity.** While in bright light, the demon has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.

**Shadow Stealth.** While in dim light or darkness, the demon can take the Hide action as a bonus action.


---

### Actions

**Claws.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 10 (2d6 + 3) psychic damage or, if the demon had advantage on the attack roll, 17 (4d6 + 3) psychic damage.


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