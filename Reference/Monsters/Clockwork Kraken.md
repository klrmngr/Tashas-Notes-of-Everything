---
type: pc
race: "Construct"
class:
 - "Clockwork Kraken"
subClass:
 - "CR 10"
cover: "Clockwork Kraken.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/10
  - source/llk
---
###### Clockwork Kraken
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Lost Laboratory of Kwalish
___

> [!infobox|no-t right]
> ![[Clockwork Kraken.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 142 (15d10 + 60) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Lost Laboratory of Kwalish |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 18 | 3 | 11 | 1 |
| **Mod** | +5 | +1 | +4 | -4 | +0 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** understands the languages of its creator but can't speak
**Damage Resistances:** fire; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Magic Resistance.** The clockwork kraken has advantage on saving throws against spells and other magical effects.

**Independent Tentacles.** The clockwork kraken has eight tentacles, each of which is treated as a Medium creature, moves independently on the construct's turn, and has a flying speed of 40 feet. The clockwork kraken's senses operate through its tentacles as well as its main body. Each tentacle can be attacked independently, with damage dealt to tentacles applied to the clockwork kraken's hit point total. A tentacle is destroyed if it takes more than 20 damage.
Reducing the construct to three or fewer tentacles reduces its attacks accordingly. A clockwork kraken can regrow any destroyed tentacles at the end of a long rest.


---

### Actions

**Multiattack.** The clockwork kraken makes four tentacle slam attacks.

**Tentacle Slam.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) bludgeoning damage.


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