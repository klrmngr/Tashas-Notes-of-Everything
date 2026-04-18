---
type: pc
race: "Undead"
class:
 - "Soul Shaker"
subClass:
 - "CR 4"
cover: "Soul Shaker.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/large
  - cr/4
  - source/jttrc
---
###### Soul Shaker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: JttRC
___

> [!infobox|no-t right]
> ![[Soul Shaker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Undead |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 76 (8d10 + 32) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | JttRC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 8 | 18 | 8 | 11 | 14 |
| **Mod** | +5 | -1 | +4 | -1 | +0 | +2 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 10
**Languages:** telepathy 60 ft.
**Damage Resistances:** necrotic
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Enthralled Lure (1/Day).** The soul shaker can cast the geas spell, requiring no spell components and using Charisma as the spellcasting ability (spell save DC 12).

**Reconstruction.** When the soul shaker is reduced to 0 hit points, it explodes into 7 (1d4 + 5) crawling claws. After 6 (1d12) days, if at least two of those crawling claws are alive, they teleport to the location of the soul shaker's death and merge together, whereupon the soul shaker reforms and regains all its hit points.

**Unusual Nature.** The soul shaker doesn't require air, food, drink, or sleep.


---

### Actions

**Crushing Grasp.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) bludgeoning damage. If the target is a Medium or smaller creature, it is grappled (escape DC 15). The soul shaker can have only one creature grappled in this way at a time.


---

### Bonus Actions

**Consume Vitality.** The soul shaker targets a creature it is grappling. If the target is not a Construct or an Undead, the target must succeed on a DC 14 Constitution saving throw or take 7 (2d6) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the soul shaker regains hit points equal to that amount. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.


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