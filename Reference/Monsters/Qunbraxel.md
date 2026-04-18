---
type: pc
race: "Aberration (mind flayer, warlock)"
class:
 - "Qunbraxel"
subClass:
 - "CR 9"
cover: "Qunbraxel.png"
campaign:
locations:
tags:
  - race/mind flayer
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/9
  - source/pabtso
---
###### Qunbraxel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Qunbraxel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Aberration (mind flayer, warlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Aberration (mind flayer, warlock) |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 17 | 19 | 15 | 19 |
| **Mod** | +0 | +2 | +3 | +4 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Deep Speech, telepathy 60 ft., Undercommon
**Saving Throws:** Int +8, Wis +6, Cha +8
**Skills:** Arcana +8, Insight +6, Perception +6, Stealth +6

---

### Traits

**Magic Resistance.** Qunbraxel has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Qunbraxel makes two Eldritch Bolt attacks, or one Eldritch Bolt attack and one Tentacle attack.

**Tentacle.** Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. *Hit:* 15 (2d10 + 4) psychic damage. If the target is Medium or smaller, it has the grappled condition (escape DC 16) and must succeed on a DC 16 Intelligence saving throw or have the stunned condition until the grapple ends.

**Eldritch Bolt.** Ranged Spell Attack: +8 to hit, range 120 ft., one target. *Hit:* 20 (3d10 + 4) force damage.

**Extract Brain.** Melee Weapon Attack: +8 to hit, reach 5 ft., one Humanoid with the stunned condition who is grappled by Qunbraxel. *Hit:* 55 (10d10) piercing damage. If this damage reduces the target to 0 hit points, Qunbraxel kills it by extracting and devouring its brain.

**Mind Blast (Recharge 5–6).** Qunbraxel magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a DC 16 Intelligence saving throw or take 26 (5d8 + 4) psychic damage and have the stunned condition for 1 minute. A stunned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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