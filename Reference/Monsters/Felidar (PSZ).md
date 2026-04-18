---
type: pc
race: "Celestial"
class:
 - "Felidar"
subClass:
 - "CR 5"
cover: "Felidar.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/5
  - source/psz
---
###### Felidar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSZ
___

> [!infobox|no-t right]
> ![[Felidar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 67 (9d10 + 18) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | PSZ |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 15 | 11 | 17 | 16 |
| **Mod** | +4 | +2 | +2 | +0 | +3 | +3 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Celestial, telepathy 60 ft.
**Damage Immunities:** poison
**Condition Immunities:** charmed; paralyzed; poisoned

---

### Traits

**Pounce.** If the felidar moves at least 20 feet straight toward a creature and then hits it with a claws attack on the same turn, the target must succeed on a DC 15 Strength saving throw or be knocked prone. If the target is prone, the felidar can make one bite attack against it as a bonus action.

**Magic Resistance.** The felidar has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The felidar's weapon attacks are magical.


---

### Actions

**Multiattack.** The felidar makes two attacks with its claws.

**Claws.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage.

**Healing Touch (3/Day).** The felidar touches another creature with its horns. The target magically regains 11 (2d8 + 2) hit points. In addition, the touch removes all diseases and neutralizes all poisons afflicting the target

**Teleport (1/Day).** The felidar magically teleports itself and up to three willing creatures it can see within 5 feet of it, along with any equipment they are wearing or carrying, to a location the felidar is familiar with, up to 1 mile away.


---

### Legendary Actions

### 

**Claws.** The felidar makes one attack with its claws.

**Shimmering Shield (Costs 2 Actions).** The felidar creates a shimmering magical field around itself or another creature it can see within 60 feet of it. The target gains a +2 bonus to AC until the end of the felidar's next turn.

**Heal Self (Costs 3 Actions).** The felidar magically regains 11 (2d8 + 2) hit points.


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