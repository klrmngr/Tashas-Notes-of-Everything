---
type: pc
race: "Undead"
class:
 - "Nightveil Specter"
subClass:
 - "CR 10"
cover: "Nightveil Specter.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/10
  - source/ggr
---
###### Nightveil Specter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Nightveil Specter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 105 (14d8 + 42) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 19 | 16 | 6 | 17 | 11 |
| **Mod** | +4 | +4 | +3 | -2 | +3 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** understands Common but can't speak
**Saving Throws:** Dex +8, Wis +7
**Skills:** Insight +7, Perception +7, Stealth +8
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Mount.** If the specter isn't mounted, it can use a bonus action to magically teleport onto its gloamwing mount, provided the specter and the gloamwing are on the same plane of existence. When it teleports, the specter appears astride the gloamwing along with any equipment it is wearing or carrying. While mounted and not incapacitated, the specter can't be surprised, and both it and its mount gain advantage on Dexterity saving throws.


---

### Actions

**Multiattack.** The specter makes two scythe attacks.

**Scythe.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage plus 13 (3d8) psychic damage.

**Mind Twist (Recharge 5–6).** The specter magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a DC 15 Wisdom saving throw or take 22 (5d8) psychic damage and be stunned for 1 minute. The stunned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Reap Memory (3/Day).** The specter touches one incapacitated creature and chooses 1 hour from among the past 24. Unless the creature succeeds on a DC 15 Intelligence saving throw, the creature loses all memory of that hour. The creature regains the memory only if the specter dies within the next 24 hours.


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