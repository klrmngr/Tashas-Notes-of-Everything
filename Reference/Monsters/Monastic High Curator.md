---
type: pc
race: "Humanoid (monk, wizard)"
class:
 - "Monastic High Curator"
subClass:
 - "CR 10"
cover: "Monastic High Curator.png"
campaign:
locations:
tags:
  - race/monk
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/10
  - source/crcotn
---
###### Monastic High Curator
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Monastic High Curator.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Small Humanoid (monk, wizard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 19 (Unarmored Defense) |
> | :FasHeart: HP | 130 (20d8 + 40) |
> | :FasUserGroup: Race | Humanoid (monk, wizard) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 14 | 18 | 22 | 17 |
| **Mod** | +1 | +3 | +2 | +4 | +6 | +3 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., passive Perception 20
**Languages:** Common plus four other languages
**Saving Throws:** Dex +7, Wis +10
**Skills:** Arcana +8, History +8, Investigation +8, Perception +10
**Damage Resistances:** psychic
**Condition Immunities:** charmed

---

### Traits

**Unarmored Defense.** While the high curator is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.


---

### Actions

**Multiattack.** The high curator makes three Force Strike attacks and uses Brain Burn (if available).

**Force Strike.** Melee or Ranged Spell Attack: +10 to hit, reach 5 ft. or range 10 ft., one target. *Hit:* 17 (2d10 + 6) force damage.

**Brain Burn (Recharge 4–6).** The high curator targets up to two creatures it can see within 30 feet of itself. Each target must make a DC 18 Constitution saving throw. On a failed saving throw, the target takes 28 (8d6) psychic damage and can't take reactions until the start of its next turn. On a successful save, the target takes half as much damage and suffers no other effect.


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