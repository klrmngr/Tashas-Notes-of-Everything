---
type: pc
race: "Giant"
class:
 - "Fog Giant"
subClass:
 - "CR 11"
cover: "Fog Giant.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/11
  - source/mff
---
###### Fog Giant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MFF
___

> [!infobox|no-t right]
> ![[Fog Giant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (chain mail) |
> | :FasHeart: HP | 200 (16d12 + 96) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | MFF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 10 | 22 | 12 | 16 | 16 |
| **Mod** | +8 | +0 | +6 | +1 | +3 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Common, Giant
**Saving Throws:** Con +10, Wis +7, Cha +7
**Skills:** Insight +7, Perception +7, Persuasion +7

---

### Traits

**Denizen of the Mist.** During its turn, the fog giant ignores the effects of fog cloud spells cast by it or other allied fog giants.

**Keen Smell.** The giant has advantage on Wisdom (Perception) checks that rely on smell.


---

### Actions

**Multiattack.** The giant makes two greatsword attacks and casts fog cloud.

**Greatsword.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 29 (6d6 + 8) slashing damage.

**Rock.** Ranged Weapon Attack: +12 to hit, range 60/240 ft., one target. *Hit:* 30 (4d10 + 8) bludgeoning damage.

**Petty Tyrant (Recharge 6).** The fog giant shouts bloodcurdling threats at the creatures that serve it. Each medium or smaller ally of the giant within 120 feet of it that can see or hear it can use its reaction to make a melee attack.


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