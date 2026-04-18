---
type: pc
race: "Monstrosity"
class:
 - "Criosphinx"
subClass:
 - "CR 13"
cover: "Criosphinx.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/13
  - source/psa
---
###### Criosphinx
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSA
___

> [!infobox|no-t right]
> ![[Criosphinx.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 228 (24d10 + 96) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | PSA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 18 | 16 | 16 | 16 |
| **Mod** | +4 | +2 | +4 | +3 | +3 | +3 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 18
**Languages:** understands Common, Sphinx
**Skills:** Arcana +8, History +8, Perception +8, Religion +8
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Inscrutable.** The sphinx is immune to any effect that would sense its emotions or read its thoughts, as well as any divination spell that it refuses. Wisdom (Insight) checks made to ascertain the sphinx's intentions or sincerity have disadvantage.

**Magic Weapons.** The sphinx's weapon attacks are magical.


---

### Actions

**Multiattack.** The sphinx makes a ram attack and two claw attacks.

**Ram.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 17 (3d8 + 4) bludgeoning damage.

**Claw.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage.


---

### Legendary Actions

### 

**Ram Attack.** The sphinx makes one ram attack.

**Teleport (Costs 2 Actions).** The sphinx magically teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied space it can see.


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