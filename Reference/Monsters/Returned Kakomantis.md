---
type: pc
race: "Undead"
class:
 - "Returned Kakomantis"
subClass:
 - "CR 4"
cover: "Returned Kakomantis.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/4
  - source/mot
---
###### Returned Kakomantis
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Returned Kakomantis.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 17 | 14 | 13 | 12 | 15 |
| **Mod** | +0 | +3 | +2 | +1 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** the languages it knew in life
**Skills:** Acrobatics +5, Athletics +2, Stealth +5
**Damage Resistances:** necrotic
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Fleeting Anger.** If another creature deals damage to the Returned, the Returned makes attack rolls with advantage until the end of its next turn.

**Turn Resistance.** The Returned has advantage on saving throws against any effect that turns undead.

**Unreadable Face.** The Returned is immune to any effect that would sense its emotions or read its thoughts. Wisdom (Insight) checks to ascertain the Returned's intentions or sincerity are made with disadvantage.


---

### Actions

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 10 (3d6) poison damage.

**Underworld Bolt.** Ranged Spell Attack: +4 to hit, range 120 ft., one creature. *Hit:* 13 (2d8 + 2) necrotic damage, and the target can't regain hit points until the start of the Returned's next turn. If the target is missing any of its hit points, it instead takes 17 (2d12 + 2) necrotic damage.


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