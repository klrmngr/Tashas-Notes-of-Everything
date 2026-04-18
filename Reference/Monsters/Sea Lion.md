---
type: pc
race: "Monstrosity"
class:
 - "Sea Lion"
subClass:
 - "CR 5"
cover: "Sea Lion.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/5
  - source/tftyp
---
###### Sea Lion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Sea Lion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 90 (12d10 + 24) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 15 | 15 | 3 | 12 | 8 |
| **Mod** | +3 | +2 | +2 | -4 | +1 | -1 |

**Speed:** 10 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** —
**Skills:** Perception +4, Stealth +5

---

### Traits

**Amphibious.** The sea lion can breathe air and water.

**Keen Smell.** The sea lion has advantage on Wisdom (Perception) checks that rely on smell.

**Pack Tactics.** The sea lion has advantage on an attack roll against a creature if at least one of the sea lion's allies is within 5 feet of the creature and the ally isn't incapacitated.

**Swimming Leap.** With a 10-foot swimming start, the sea lion can long jump out of or across the water up to 25 feet.


---

### Actions

**Multiattack.** The sea lion makes three attacks: one bite attack and two claw attacks.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 12 (2d8 + 3) piercing damage.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 12 (2d8 + 3) piercing damage.


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