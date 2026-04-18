---
type: pc
race: "Monstrosity"
class:
 - "Space Hamster"
subClass:
 - "CR 1/4"
cover: "Space Hamster.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/tiny
  - cr/1-4
  - source/bam
---
###### Space Hamster
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Space Hamster.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Tiny Monstrosity |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 10 (4d4) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 20 | 10 | 6 | 12 | 6 |
| **Mod** | -5 | +5 | +0 | -2 | +1 | -2 |

**Speed:** 20 ft., burrow 5 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** telepathy 5 ft.
**Skills:** Perception +3, Stealth +7

---

### Actions

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 1 piercing damage.

**Go for the Eyes (Recharge 6).** Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. *Hit:* 8 (1d6 + 5) piercing damage, and the target must succeed on a DC 15 Dexterity saving throw or be blinded until the start of the hamster's next turn.


---

### Bonus Actions

**Escape.** The hamster takes the Dash or Disengage action.


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