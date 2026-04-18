---
type: pc
race: "Fey"
class:
 - "High Fae Impostor"
subClass:
 - "CR 11"
cover: "High Fae Impostor.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/11
  - source/mcv4ec
---
###### High Fae Impostor
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[High Fae Impostor.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 149 (23d8 + 46) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 21 | 15 | 18 | 16 | 23 |
| **Mod** | +1 | +5 | +2 | +4 | +3 | +6 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Sylvan
**Saving Throws:** Dex +9, Wis +7
**Skills:** Deception +14, Performance +10, Stealth +13
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Magic Resistance.** The high fae has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The high fae makes two Fae Blade attacks and uses Vexing Prank once.

**Fae Blade.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 18 (3d8 + 5) force damage.

**Vexing Prank.** The high fae targets one creature it can see within 60 feet of itself with a magical trick. The target must make a DC 18 Wisdom saving throw. On a failed save, the target takes 21 (6d6) psychic damage and has the frightened condition until the start of the high fae's next turn. On a successful save, the target takes half as much damage only.


---

### Bonus Actions

**Loot Likeness.** The high fae magically transforms into a duplicate of a Small or Medium creature it can see. While transformed, the high fae retains its game statistics (other than its size) but gains access to enough general information about the imitated creature, such as background and personality, to reasonably pass itself off as the creature. This transformation ends if the high fae is reduced to 0 hit points, uses this bonus action again, or uses a bonus action to revert to its true form.


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