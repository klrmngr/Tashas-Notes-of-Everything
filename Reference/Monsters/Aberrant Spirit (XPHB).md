---
type: pc
race: "Aberration"
class:
 - "Aberrant Spirit"
subClass:
 - "CR —"
cover: "Aberrant Spirit.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/—
  - source/xphb
---
###### Aberrant Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XPHB
___

> [!infobox|no-t right]
> ![[Aberrant Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC |  |
> | :FasHeart: HP | 40 + 10 for each spell level above 4 |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XPHB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 15 | 16 | 10 | 6 |
| **Mod** | +3 | +0 | +2 | +3 | +0 | -2 |

**Speed:** 30 ft., fly 30 ft. ((hover; Beholderkin only)) (hover) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Deep Speech, understands the languages you know
**Damage Immunities:** psychic

---

### Traits

**Regeneration (Slaad Only).** The spirit regains 5 Hit Points at the start of its turn if it has at least 1 Hit Point.

**Whispering Aura (Mind Flayer Only).** At the start of each of the spirit's turns, the spirit emits psionic energy if it doesn't have the Incapacitated condition. wis DC equals your spell save DC, each creature (other than you) within 5 feet of the spirit.  2d6 Psychic damage.


---

### Actions

**Multiattack.** The spirit makes a number of attacks equal to half this spell's level (round down).

**Claw (Slaad Only).** m Bonus equals your spell attack modifier, reach 5 ft. *Hit:* 1d10 + 3 + summonSpellLevel Slashing damage, and the target can't regain Hit Points until the start of the spirit's next turn.

**Eye Ray (Beholderkin Only).** r Bonus equals your spell attack modifier, range 150 ft. *Hit:* 1d8 + 3 + summonSpellLevel Psychic damage.

**Psychic Slam (Mind Flayer Only).** m Bonus equals your spell attack modifier, reach 5 ft. *Hit:* 1d8 + 3 + summonSpellLevel Psychic damage.


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