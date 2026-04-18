---
type: pc
race: "Undead"
class:
 - "Allip"
subClass:
 - "CR 5"
cover: "Allip.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/5
  - source/mtf
---
###### Allip
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Allip.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 40 (9d8) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 17 | 10 | 17 | 15 | 16 |
| **Mod** | -2 | +3 | +0 | +3 | +2 | +3 |

**Speed:** 0 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** the languages it knew in life
**Saving Throws:** Int +6, Wis +5
**Skills:** Perception +5, Stealth +6
**Damage Resistances:** acid; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** cold; necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Incorporeal Movement.** The allip can move through other creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends its turn inside an object.


---

### Actions

**Maddening Touch.** Melee Spell Attack: +6 to hit, reach 5 ft., one target. *Hit:* 17 (4d6 + 3) psychic damage.

**Whispers of Madness.** The allip chooses up to three creatures it can see within 60 feet of it. Each target must succeed on a DC 14 Wisdom saving throw, or it takes 7 (1d8 + 3) psychic damage and must use its reaction to make a melee weapon attack against one creature of the allip's choice that the allip can see. Constructs and undead are immune to this effect.

**Howling Babble (Recharge 6).** Each creature within 30 feet of the allip that can hear it must make a DC 14 Wisdom saving throw. On a failed save, a target takes 12 (2d8 + 3) psychic damage, and it is stunned until the end of its next turn. On a successful save, it takes half as much damage and isn't stunned. Constructs and undead are immune to this effect.


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