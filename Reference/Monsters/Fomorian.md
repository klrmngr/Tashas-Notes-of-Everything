---
type: pc
race: "Giant"
class:
 - "Fomorian"
subClass:
 - "CR 8"
cover: "Fomorian.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/8
  - source/mm
---
###### Fomorian
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Fomorian.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 149 (13d12 + 65) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 20 | 9 | 14 | 6 |
| **Mod** | +6 | +0 | +5 | -1 | +2 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 18
**Languages:** Giant, Undercommon
**Skills:** Perception +8, Stealth +3

---

### Actions

**Multiattack.** The fomorian attacks twice with its greatclub or makes one greatclub attack and uses Evil Eye once.

**Greatclub.** Melee Weapon Attack: +9 to hit, reach 15 ft., one target. *Hit:* 19 (3d8 + 6) bludgeoning damage.

**Evil Eye.** The fomorian magically forces a creature it can see within 60 feet of it to make a DC 14 Charisma saving throw. The creature takes 27 (6d8) psychic damage on a failed save, or half as much damage on a successful one.

**Curse of the Evil Eye (Recharges after a Short or Long Rest).** With a stare, the fomorian uses Evil Eye, but on a failed save, the creature is also cursed with magical deformities. While deformed, the creature has its speed halved and has disadvantage on ability checks, saving throws, and attacks based on Strength or Dexterity.
The transformed creature can repeat the saving throw whenever it finishes a long rest, ending the effect on a success.


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