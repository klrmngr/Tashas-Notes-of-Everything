---
type: pc
race: "Undead"
class:
 - "Deathlock Mastermind"
subClass:
 - "CR 8"
cover: "Deathlock Mastermind.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/8
  - source/mtf
---
###### Deathlock Mastermind
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Deathlock Mastermind.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13; 16 with mage armor |
> | :FasHeart: HP | 110 (20d8 + 20) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 12 | 15 | 12 | 17 |
| **Mod** | +0 | +3 | +1 | +2 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft. (including magical darkness), passive Perception 14
**Languages:** the languages it knew in life
**Saving Throws:** Int +5, Cha +6
**Skills:** Arcana +5, History +5, Perception +4
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Turn Resistance.** The deathlock has advantage on saving throws against any effect that turns undead.


---

### Actions

**Deathly Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 13 (3d6 + 3) necrotic damage).

**Grave Bolts.** Ranged Spell Attack: +6 to hit, range 120 ft., one or two targets. *Hit:* 18 (4d8) necrotic damage. If the target is Large or smaller, it must succeed on a DC 16 Strength saving throw or become restrained as shadowy tendrils wrap around it for 1 minute. A restrained target can use its action to repeat the saving throw, ending the effect on itself on a success.


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