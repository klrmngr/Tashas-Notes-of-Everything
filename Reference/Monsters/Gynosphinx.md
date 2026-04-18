---
type: pc
race: "Monstrosity"
class:
 - "Gynosphinx"
subClass:
 - "CR 11"
cover: "Gynosphinx.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/11
  - source/mm
---
###### Gynosphinx
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Gynosphinx.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 136 (16d10 + 48) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 16 | 18 | 18 | 18 |
| **Mod** | +4 | +2 | +3 | +4 | +4 | +4 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 18
**Languages:** Common, Sphinx
**Skills:** Arcana +12, History +12, Perception +8, Religion +8
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Inscrutable.** The sphinx is immune to any effect that would sense its emotions or read its thoughts, as well as any divination spell that it refuses. Wisdom (Insight) checks made to ascertain the sphinx's intentions or sincerity have disadvantage.

**Magic Weapons.** The sphinx's weapon attacks are magical.


---

### Actions

**Multiattack.** The sphinx makes two claw attacks.

**Claw.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage.


---

### Legendary Actions

### 

**Claw Attack.** The sphinx makes one claw attack.

**Teleport (Costs 2 Actions).** The sphinx magically teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied space it can see.

**Cast a Spell (Costs 3 Actions).** The sphinx casts a spell from its list of prepared spells, using a spell slot as normal.


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