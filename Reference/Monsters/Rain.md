---
type: pc
race: "Celestial"
class:
 - "Rain"
subClass:
 - "CR 5"
cover: "Rain.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/small
  - cr/5
  - source/mismv1
---
###### Rain
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MisMV1
___

> [!infobox|no-t right]
> ![[Rain.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Small Celestial |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 60 (11d6 + 22) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | MisMV1 |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 11 | 14 | 14 | 18 | 15 |
| **Mod** | +0 | +0 | +2 | +2 | +4 | +2 |

**Speed:** 30 ft., fly 120 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Celestial, Common
**Saving Throws:** Dex +3, Con +5, Wis +7
**Skills:** Acrobatics +3, Insight +7, Stealth +3
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** fire; poison; radiant
**Condition Immunities:** charmed; paralyzed; poisoned

---

### Traits

**Fiery Wings.** Rain's wings are made of flame, and they shed bright light out to 15 feet and dim light for an additional 15 feet. At the start of each of Rain's turns, each creature of Rain's choice within 5 feet of her takes 3 (1d6) fire damage. A creature that hits Rain with a melee attack takes 3 (1d6) fire damage.

**Magic Resistance.** Rain has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Rain makes two Hoof attacks.

**Hoof.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 5 (2d4) bludgeoning damage.

**Haloed Horn Burst (Recharge 5–6).** Rain uses her haloed horn to produce one of the following magical effects:

**Glitterstorm.** Rain emits a rainbow beam in a 30-foot line that is 5 feet wide. Each creature in that area must make a DC 15 Dexterity saving throw, taking 21 (6d6) radiant damage on a failed saving throw, or half as much damage on a successful one; creatures of evil alignment have disadvantage on this saving throw. If the damage from this effect reduces a creature to 0 hit points, the creature dies, and its body turns into glittery flowers.

**Healing Rainbows.** Rain releases a wave of rejuvenating multicolored light in a 30-foot cone. Each creature of Rain's choice in that area regains 18 (4d8) hit points.


---

### Bonus Actions

**Nimble Escape.** Rain takes either the Disengage or the Hide action.


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