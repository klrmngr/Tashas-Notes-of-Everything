---
type: pc
race: "Humanoid (elf)"
class:
 - "Drow House Captain"
subClass:
 - "CR 9"
cover: "Drow House Captain.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/mtf
---
###### Drow House Captain
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Drow House Captain.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (chain mail) |
> | :FasHeart: HP | 162 (25d8 + 50) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 19 | 15 | 12 | 14 | 13 |
| **Mod** | +2 | +4 | +2 | +1 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Elvish, Undercommon
**Saving Throws:** Dex +8, Con +6, Wis +6
**Skills:** Perception +6, Stealth +8

---

### Traits

**Battle Command.** As a bonus action, the drow targets one ally he can see within 30 feet of him. If the target can see or hear the drow, the target can use its reaction to make one melee attack or to take the Dodge or Hide action.

**Fey Ancestry.** The drow has advantage on saving throws against being charmed, and magic can't put the drow to sleep.

**Sunlight Sensitivity.** While in sunlight, the drow has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The drow makes three attacks: two with his scimitar and one with his whip or his hand crossbow.

**Scimitar.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage plus 14 (4d6) poison damage.

**Whip.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 6 (1d4 + 4) slashing damage. If the target is an ally, it has advantage on attack rolls until the end of its next turn.

**Hand Crossbow.** Ranged Weapon Attack: +8 to hit, range 30/120 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage, and the target must succeed on a DC 13 Constitution saving throw or be poisoned for 1 hour. If the saving throw fails by 5 or more, the target is also unconscious while poisoned in this way. The target regains consciousness if it takes damage or if another creature takes an action to shake it.


---

### Reactions

**Parry.** The drow adds 3 to his AC against one melee attack that would hit him. To do so, the drow must see the attacker and be wielding a melee weapon.


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