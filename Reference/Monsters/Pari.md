---
type: pc
race: "Celestial"
class:
 - "Pari"
subClass:
 - "CR 13"
cover: "Pari.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/13
  - source/jttrc
---
###### Pari
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: JttRC
___

> [!infobox|no-t right]
> ![[Pari.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 180 (19d8 + 95) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | JttRC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 20 | 20 | 20 | 22 | 22 |
| **Mod** | +5 | +5 | +5 | +5 | +6 | +6 |

**Speed:** 30 ft., fly 90 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 21
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Con +10, Wis +11, Cha +11
**Skills:** Insight +16, Perception +11
**Damage Resistances:** fire; radiant; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Magic Resistance.** The pari has advantage on saving throws against spells and other magical effects.

**Unusual Nature.** The pari doesn't require food, drink, or sleep.


---

### Actions

**Multiattack.** The pari makes three Mace attacks.

**Mace.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 8 (1d6 + 5) bludgeoning damage plus 14 (4d6) radiant damage.

**Disorienting Futures.** The pari attempts to flood the mind of one creature it can see within 60 feet of itself with visions of the future. The target must succeed on a DC 19 Wisdom saving throw or take 27 (5d10) psychic damage and have disadvantage on attack rolls until the start of the pari's next turn.


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