---
type: pc
race: "Construct"
class:
 - "Bore Worm"
subClass:
 - "CR 16"
cover: "Bore Worm.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/gargantuan
  - cr/16
  - source/wdmm
---
###### Bore Worm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDMM
___

> [!infobox|no-t right]
> ![[Bore Worm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Gargantuan Construct |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 247 (15d20 + 90) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | WDMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 7 | 22 | 1 | 8 | 4 |
| **Mod** | +9 | -2 | +6 | -5 | -1 | -3 |

**Speed:** 50 ft., burrow 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., tremorsense 60 ft., passive Perception 9
**Languages:** —
**Saving Throws:** Con +11, Wis +4
**Damage Immunities:** poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned; prone

---

### Traits

**Tunneler.** The worm can burrow through solid rock at half its burrow speed and leaves a 10-foot-diameter tunnel in its wake.

**Regeneration.** The worm regains 10 hit points at the start of each of its turns if it has at least 1 hit point.


---

### Actions

**Multiattack.** The worm makes two attacks: one with its grinding jaws and one with its stinger.

**Grinding Jaws.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 22 (3d8 + 9) slashing damage.

**Tail Stinger.** Melee Weapon Attack: +14 to hit, reach 10 ft., one creature. *Hit:* 19 (3d6 + 9) piercing damage, and the target must make a DC 19 Constitution saving throw, taking 42 (12d6) poison damage on a failed save, or half as much damage on a successful one.


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