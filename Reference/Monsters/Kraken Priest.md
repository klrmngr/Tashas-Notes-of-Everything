---
type: pc
race: "Monstrosity"
class:
 - "Kraken Priest"
subClass:
 - "CR 5"
cover: "Kraken Priest.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/5
  - source/mpmm
---
###### Kraken Priest
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Kraken Priest.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 10 | 16 | 10 | 15 | 14 |
| **Mod** | +1 | +0 | +3 | +0 | +2 | +2 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** any two languages
**Skills:** Perception +5

---

### Traits

**Amphibious.** The priest can breathe air and water.


---

### Actions

**Multiattack.** The priest makes two Thunderous Touch or Thunderbolt attacks.

**Thunderous Touch.** Melee Spell Attack: +5 to hit, reach 5 ft., one target. *Hit:* 27 (5d10) thunder damage.

**Thunderbolt.** Ranged Spell Attack: +5 to hit, range 60 ft., one target. *Hit:* 11 (2d10) lightning damage plus 11 (2d10) thunder damage, and the target is knocked prone.

**Voice of the Kraken (Recharges after a Short or Long Rest).** A kraken speaks through the priest with a thunderous voice audible within 300 feet. Creatures of the priest's choice that can hear the kraken's words (which are spoken in Abyssal, Infernal, or Primordial) must succeed on a DC 14 Wisdom saving throw or be frightened of the priest for 1 minute. A frightened target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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