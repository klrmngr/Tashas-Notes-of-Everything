---
type: pc
race: "Fey"
class:
 - "High Fae Noble"
subClass:
 - "CR 13"
cover: "High Fae Noble.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/13
  - source/mcv4ec
---
###### High Fae Noble
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[High Fae Noble.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 175 (27d8 + 54) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 25 | 15 | 19 | 18 | 22 |
| **Mod** | +1 | +7 | +2 | +4 | +4 | +6 |

**Speed:** 40 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 19
**Languages:** Common, Sylvan, telepathy 120 ft.
**Saving Throws:** Dex +12, Int +9, Wis +9, Cha +11
**Skills:** History +9, Insight +14, Perception +9
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Aura of Overwhelming Splendor.** The high fae radiates dazzling and mollifying magic. Each creature of the high fae's choice that starts its turn within 5 feet of the high fae must succeed on a DC 19 Wisdom saving throw or have the charmed condition until the start of its next turn. While charmed, the creature also has the incapacitated condition.

**Legendary Resistance (3/Day).** If the high fae fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The high fae has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The high fae makes two Fae Blade attacks. It can replace one of these attacks with Stunning Soliloquy if available.

**Fae Blade.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 20 (3d8 + 7) force damage.

**Stunning Soliloquy (Recharge 5–6).** The high fae unleashes a string of magical words. Each creature of the high fae's choice within 30 feet of itself must succeed on a DC 19 Wisdom saving throw or have the stunned condition for 1 minute. A stunned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Reactions

**Capricious Step.** Immediately after taking damage, the high fae magically has the invisible condition and teleports, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 30 feet of itself. The invisibility lasts until the end of the high fae's next turn.

**Ridicule.** When a creature misses the high fae with an attack roll, the high fae magically mocks the creature, dealing 5 (2d4) psychic damage to the attacker.


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