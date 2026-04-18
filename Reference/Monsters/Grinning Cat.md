---
type: pc
race: "Fey"
class:
 - "Grinning Cat"
subClass:
 - "CR 1"
cover: "Grinning Cat.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/large
  - cr/1
  - source/bgg
---
###### Grinning Cat
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Grinning Cat.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Fey |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 45 (7d10 + 7) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 15 | 13 | 15 | 14 | 16 |
| **Mod** | +2 | +2 | +1 | +2 | +2 | +3 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common, Sylvan
**Skills:** Perception +4, Stealth +6

---

### Traits

**Magic Resistance.** The grinning cat has advantage on saving throws against spells and other magical effects.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage.

**Claws.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 9 (2d6 + 2) slashing damage. If the grinning cat was invisible before it attacked, the target must succeed on a DC 12 Strength saving throw or have the prone condition. If the target has the prone condition, the cat can make a Bite attack against it as a bonus action.

**Fade Away.** The grinning cat magically becomes invisible for 1 hour or until it attacks, gradually fading away over the course of its turn. It can choose to leave part of its body visible, such as its tail, its head, or its grinning mouth. Any equipment the cat wears or carries is invisible with it.


---

### Bonus Actions

**Fade Back.** The grinning cat becomes visible or makes part of its body visible. Any equipment the cat wears or carries on a visible part of its body also becomes visible.

**Grinning Step.** The grinning cat teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see.


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