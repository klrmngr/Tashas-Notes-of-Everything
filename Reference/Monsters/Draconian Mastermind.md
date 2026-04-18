---
type: pc
race: "Monstrosity"
class:
 - "Draconian Mastermind"
subClass:
 - "CR 6"
cover: "Draconian Mastermind.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/6
  - source/ftd
---
###### Draconian Mastermind
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Draconian Mastermind.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 67 (9d8 + 27) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 14 | 16 | 15 | 11 | 17 |
| **Mod** | +1 | +2 | +3 | +2 | +0 | +3 |

**Speed:** 35 ft. &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 13
**Languages:** Common, Draconic
**Saving Throws:** Int +5, Wis +3, Cha +6
**Skills:** Perception +3
**Condition Immunities:** charmed

---

### Traits

**Death Throes.** When the draconian is reduced to 0 hit points, its magical essence lashes out as a ball of lightning at the closest creature within 30 feet of it before arcing out to up to two other creatures within 15 feet of the first. Each creature must make a DC 14 Dexterity saving throw. On a failed save, the creature takes 9 (2d8) lightning damage and is stunned until the end of its next turn. On a successful save, the creature takes half as much damage and isn't stunned.


---

### Actions

**Multiattack.** The draconian makes three Rend or Energy Ray attacks.

**Rend.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) slashing damage.

**Energy Ray.** Ranged Spell Attack: +6 to hit, range 60 ft., one target. *Hit:* 8 (1d10 + 3) force damage.

**Noxious Breath (Recharge 5–6).** The draconian exhales a 15-foot cone of noxious gas. Each creature in that area must make a DC 14 Constitution saving throw. On a failed save, the creature takes 21 (6d6) poison damage and gains 1 level of exhaustion. On a successful save, the creature takes half as much damage, doesn't gain exhaustion, and is immune to all draconians' Noxious Breath for 24 hours.


---

### Reactions

**Magic Shield (3/Day).** When the draconian is hit by an attack roll, it can create an invisible barrier of magical force around itself, granting it a +5 bonus to its AC against that attack and potentially causing the attack to miss.


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