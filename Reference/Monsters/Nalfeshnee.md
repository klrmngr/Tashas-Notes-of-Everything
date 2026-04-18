---
type: pc
race: "Fiend (demon)"
class:
 - "Nalfeshnee"
subClass:
 - "CR 13"
cover: "Nalfeshnee.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/13
  - source/mm
---
###### Nalfeshnee
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Nalfeshnee.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 184 (16d10 + 96) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 10 | 22 | 19 | 12 | 15 |
| **Mod** | +5 | +0 | +6 | +4 | +1 | +2 |

**Speed:** 20 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 11
**Languages:** Abyssal, telepathy 120 ft.
**Saving Throws:** Con +11, Int +9, Wis +6, Cha +7
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The nalfeshnee has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The nalfeshnee uses Horror Nimbus if it can. It then makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 32 (5d10 + 5) piercing damage.

**Claw.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 15 (3d6 + 5) slashing damage.

**Horror Nimbus (Recharge 5–6).** The nalfeshnee magically emits scintillating, multicolored light. Each creature within 15 feet of the nalfeshnee that can see the light must succeed on a DC 15 Wisdom saving throw or be frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the nalfeshnee's Horror Nimbus for the next 24 hours.

**Teleport.** The nalfeshnee magically teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied space it can see.


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