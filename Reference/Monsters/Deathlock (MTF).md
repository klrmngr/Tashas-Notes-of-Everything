---
type: pc
race: "Undead"
class:
 - "Deathlock"
subClass:
 - "CR 4"
cover: "Deathlock.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/4
  - source/mtf
---
###### Deathlock
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Deathlock.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 36 (8d8) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 15 | 10 | 14 | 12 | 16 |
| **Mod** | +0 | +2 | +0 | +2 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** the languages it knew in life
**Saving Throws:** Int +4, Cha +5
**Skills:** Arcana +4, History +4
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Turn Resistance.** The deathlock has advantage on saving throws against any effect that turns undead.


---

### Actions

**Deathly Claw.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 9 (2d6 + 2) necrotic damage.


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