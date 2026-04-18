---
type: pc
race: "Construct (inevitable)"
class:
 - "Marut"
subClass:
 - "CR 25"
cover: "Marut.png"
campaign:
locations:
tags:
  - race/inevitable
  - affinity/hostile
  - type/construct
  - size/large
  - cr/25
  - source/mpmm
---
###### Marut
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Marut.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 25 (75,000 XP) |
> | :RiSwordFill: Type | Large Construct (inevitable) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 22 (natural armor) |
> | :FasHeart: HP | 432 (32d10 + 256) |
> | :FasUserGroup: Race | Construct (inevitable) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 12 | 26 | 19 | 15 | 18 |
| **Mod** | +9 | +1 | +8 | +4 | +2 | +4 |

**Speed:** 40 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 20
**Languages:** all but rarely speaks
**Saving Throws:** Int +12, Wis +10, Cha +12
**Skills:** Insight +10, Intimidation +12, Perception +10
**Damage Resistances:** thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; paralyzed; poisoned; unconscious

---

### Traits

**Immutable Form.** The marut is immune to any spell or effect that would alter its form.

**Legendary Resistance (3/Day).** If the marut fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The marut has advantage on saving throws against spells and other magical effects.

**Unusual Nature.** The marut doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The marut makes two Unerring Slam attacks.

**Unerring Slam.** Melee Weapon Attack: automatic hit, reach 5 ft., one target. *Hit:* 60 force damage, and the target is pushed up to 5 feet away from the marut if it is Huge or smaller.

**Blazing Edict (Recharge 5–6).** Arcane energy emanates from the marut's chest in a 60-foot cube. Every creature in that area takes 45 radiant damage. Each creature that takes any of this damage must succeed on a DC 20 Wisdom saving throw or be stunned until the end of the marut's next turn.


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