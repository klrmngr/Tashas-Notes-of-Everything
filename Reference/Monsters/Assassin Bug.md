---
type: pc
race: "Monstrosity"
class:
 - "Assassin Bug"
subClass:
 - "CR 3"
cover: "Assassin Bug.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/3
  - source/mff
---
###### Assassin Bug
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MFF
___

> [!infobox|no-t right]
> ![[Assassin Bug.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 55 (10d8 + 10) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | MFF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 14 | 13 | 4 | 12 | 6 |
| **Mod** | +1 | +2 | +1 | -3 | +1 | -2 |

**Speed:** 10 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** understands Druidic but can't speak
**Skills:** Perception +3, Stealth +4
**Damage Resistances:** poison
**Condition Immunities:** paralyzed

---

### Traits

**Keen Smell.** The assassin bug has advantage on Wisdom (Perception) checks that rely on smell.


---

### Actions

**Multiattack.** The assassin bug makes two bite attacks.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 7 (1d10 + 2) piercing damage, and the target must succeed on a DC 11 Constitution saving throw or be poisoned for 1 minute. While poisoned this way, the target is paralyzed. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Ovipositor.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* The target is infested with 1d3 assassin bug eggs, which immediately hatch into assassin bug maggots. At the start of each of the target's turns, the target takes 1d6 piercing damage per maggot infesting it. Applying fire to the bite wound before the end of the target's next turn deals 1 fire damage to the target and kills these assassin bug maggots. After this time, the maggots are too far under the skin to be burned.
If a target infested by assassin bug maggots ends its turn with 0 hit points, it dies as the maggots burrow into its heart and kill it. Any effect that cures disease kills all assassin bug maggots infesting the target.


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