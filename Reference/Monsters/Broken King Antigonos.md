---
type: pc
race: "Monstrosity"
class:
 - "Broken King Antigonos"
subClass:
 - "CR 3"
cover: "Broken King Antigonos.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/3
  - source/mot
---
###### Broken King Antigonos
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Broken King Antigonos.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 38 (9d10 + 27) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 16 | 6 | 16 | 9 |
| **Mod** | +4 | +0 | +3 | -2 | +3 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** Abyssal
**Skills:** Perception +7

---

### Traits

**Charge.** If Antigonos moves at least 10 feet straight toward a target and then hits it with a gore attack on the same turn, the target takes an extra 9 (2d8) piercing damage. If the target is a creature, it must succeed on a DC 14 Strength saving throw or be pushed up to 10 feet away and knocked prone.

**Labyrinthine Recall.** Antigonos can perfectly recall any path he has traveled.

**Reckless.** At the start of his turn, Antigonos can gain advantage on all melee weapon attack rolls he makes during that turn, but attack rolls against him have advantage until the start of his next turn.

**Decrepit State.** Antigonos has disadvantage on his attack rolls.


---

### Actions

**Greataxe.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 17 (2d12 + 4) slashing damage.

**Gore.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) piercing damage.

**Amphora.** Melee Weapon Attack: +6 to hit, reach 5 ft., one Medium or smaller creature. *Hit:* 8 (1d8 + 4) bludgeoning damage. If there is not already a creature inside the amphora, the target is restrained inside. As an action, the restrained creature can make a DC 14 Dexterity (Acrobatics) check, escaping from the amphora on a success. The effect also ends if the amphora is destroyed. The amphora has AC 8, 20 hit points, and immunity to poison and psychic damage.


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