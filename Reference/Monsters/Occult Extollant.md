---
type: pc
race: "Humanoid (sorcerer)"
class:
 - "Occult Extollant"
subClass:
 - "CR 6"
cover: "Occult Extollant.png"
campaign:
locations:
tags:
  - race/sorcerer
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/6
  - source/crcotn
---
###### Occult Extollant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Occult Extollant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Small Humanoid (sorcerer) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 91 (14d8 + 28) |
> | :FasUserGroup: Race | Humanoid (sorcerer) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 15 | 14 | 16 | 15 | 18 |
| **Mod** | +1 | +2 | +2 | +3 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Common plus two other languages
**Saving Throws:** Wis +5, Cha +7
**Skills:** Arcana +6, Deception +7, History +9, Perception +5, Stealth +8
**Damage Resistances:** psychic

---

### Actions

**Multiattack.** The extollant makes two Crimson Bolt attacks.

**Crimson Bolt.** Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 60 ft., one creature. *Hit:* 20 (3d10 + 4) psychic damage.


---

### Reactions

**Reflect Agony.** When the extollant is damaged by a creature within 60 feet of it, the creature must make a DC 15 Wisdom saving throw, taking 16 (3d10) psychic damage on a failed saving throw, or half as much damage on a successful one.


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