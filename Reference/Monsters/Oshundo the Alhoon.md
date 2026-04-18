---
type: pc
race: "Undead (mind flayer, wizard)"
class:
 - "Oshundo the Alhoon"
subClass:
 - "CR 10"
cover: "Oshundo the Alhoon.png"
campaign:
locations:
tags:
  - race/mind flayer
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/10
  - source/pabtso
---
###### Oshundo the Alhoon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Oshundo the Alhoon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Undead (mind flayer, wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 150 (20d8 + 60) |
> | :FasUserGroup: Race | Undead (mind flayer, wizard) |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 12 | 16 | 19 | 17 | 17 |
| **Mod** | +0 | +1 | +3 | +4 | +3 | +3 |

**Speed:** 30 ft., fly 15 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 17
**Languages:** Common, Deep Speech, telepathy 120 ft., Undercommon
**Saving Throws:** Con +7, Int +8, Wis +7, Cha +7
**Skills:** Arcana +8, History +8, Insight +7, Perception +7, Stealth +5
**Damage Resistances:** cold; lightning; necrotic
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Magic Resistance.** Oshundo has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Oshundo makes two Chilling Grasp or Arcane Bolt attacks.

**Chilling Grasp.** Melee Spell Attack: +8 to hit, reach 5 ft., one target. *Hit:* 14 (4d6) cold damage, and Oshundo regains 14 hit points if the target is a creature.

**Arcane Bolt.** Ranged Spell Attack: +8 to hit, range 120 ft., one target. *Hit:* 28 (8d6) force damage.

**Thundering Blast (Recharge 5–6).** Oshundo emits a wave of domineering energy in a 60-foot cone. Each creature in that area must succeed on a DC 16 Intelligence saving throw or take 22 (4d8 + 4) thunder damage and have the stunned condition for 1 minute. A stunned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Reactions

**Negate Spell (3/Day).** Oshundo targets one creature it can perceive within 60 feet of itself that is casting a spell. If the spell is 3rd level or lower, the spell fails, but any spell slots or charges aren't wasted.


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