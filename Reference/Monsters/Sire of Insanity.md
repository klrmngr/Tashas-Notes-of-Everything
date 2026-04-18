---
type: pc
race: "Fiend (demon)"
class:
 - "Sire of Insanity"
subClass:
 - "CR 12"
cover: "Sire of Insanity.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/12
  - source/ggr
---
###### Sire of Insanity
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Sire of Insanity.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 157 (15d12 + 60) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 6 | 19 | 14 | 19 | 22 |
| **Mod** | +6 | -2 | +4 | +2 | +4 | +6 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 14
**Languages:** Abyssal, Common, telepathy 120 ft.
**Saving Throws:** Con +8, Int +6, Wis +8, Cha +10
**Skills:** Deception +10, Intimidation +10
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Aura of Mind Erosion.** Any creature that starts its turn within 30 feet of the sire must make a DC 18 Wisdom saving throw. On a successful save, the creature is immune to this aura for the next 24 hours. On a failed save, the creature has disadvantage for 1 minute on Wisdom and Charisma checks and on Wisdom and Charisma saves. At the start of each of its turns, the sire can suppress this aura until the start of its next turn.

**Magic Resistance.** The sire has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The sire makes two attacks: one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +10 to hit, reach 5 ft., one creature. *Hit:* 25 (3d12 + 6) piercing damage plus 16 (3d10) psychic damage.

**Claws.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 10 (1d8 + 6) slashing damage plus 9 (2d8) psychic damage.


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