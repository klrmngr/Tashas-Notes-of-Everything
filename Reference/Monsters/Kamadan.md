---
type: pc
race: "Monstrosity"
class:
 - "Kamadan"
subClass:
 - "CR 4"
cover: "Kamadan.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/4
  - source/toa
---
###### Kamadan
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Kamadan.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 67 (9d10 + 18) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 14 | 3 | 14 | 10 |
| **Mod** | +3 | +3 | +2 | -4 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** —
**Skills:** Perception +4, Stealth +7

---

### Traits

**Keen Smell.** The kamadan has advantage on Wisdom (Perception) checks that rely on smell.

**Pounce.** If the kamadan moves at least 20 feet straight toward a creature and then hits it with a claw attack on the same turn that target must succeed on a DC 13 Strength saving throw or be knocked prone. If the target is knocked prone, the kamadan can make two attacks—one with its bite and one with its snakes—against it as a bonus action.


---

### Actions

**Multiattack.** The kamadan makes two attacks: one with its bite or claw and one with its snakes.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

**Claw.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.

**Snakes.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 6 (1d6 + 3) piercing damage, and the target must make a DC 12 Constitution saving throw, taking 21 (6d6) poison damage on a failed save, or half as much damage on a successful one.

**Sleep Breath (Recharges after a Short or Long Rest).** The kamadan exhales sleep gas in a 30-foot cone. Each creature in that area must succeed on a DC 12 Constitution saving throw or fall unconscious for 10 minutes. This effect ends for a creature if it takes damage or someone uses an action to wake it.


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