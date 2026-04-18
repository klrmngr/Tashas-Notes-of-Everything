---
type: pc
race: "Construct"
class:
 - "Cadaver Collector"
subClass:
 - "CR 14"
cover: "Cadaver Collector.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/14
  - source/mpmm
---
###### Cadaver Collector
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Cadaver Collector.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 189 (18d10 + 90) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 14 | 20 | 5 | 11 | 8 |
| **Mod** | +5 | +2 | +5 | -3 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands all languages but can't speak
**Damage Immunities:** necrotic; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Magic Resistance.** The collector has advantage on saving throws against spells and other magical effects.

**Unusual Nature.** The collector doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The collector makes two Slam attacks.

**Slam.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 18 (3d8 + 5) bludgeoning damage plus 16 (3d10) necrotic damage.

**Paralyzing Breath (Recharge 5–6).** The collector releases paralyzing gas in a 30-foot cone. Each creature in that area must make a successful DC 18 Constitution saving throw or be paralyzed for 1 minute. A paralyzed creature repeats the saving throw at the end of each of its turns, ending the effect on itself with a success.


---

### Bonus Actions

**Summon Specters (Recharges after a Short or Long Rest).** The collector calls up the enslaved spirits of those it has slain; 1d4 [[Specter|specters]] (without Sunlight Sensitivity) arise in unoccupied spaces within 15 feet of it. The specters act right after the collector on the same initiative count and fight until they're destroyed. They disappear when the collector is destroyed.


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