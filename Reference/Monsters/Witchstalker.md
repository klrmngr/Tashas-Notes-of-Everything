---
type: pc
race: "Monstrosity"
class:
 - "Witchstalker"
subClass:
 - "CR 6"
cover: "Witchstalker.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/6
  - source/mcv4ec
---
###### Witchstalker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Witchstalker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 82 (11d10 + 22) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 16 | 15 | 8 | 12 | 6 |
| **Mod** | +4 | +3 | +2 | -1 | +1 | -2 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 17
**Languages:** understands Common but can't speak
**Saving Throws:** Str +7, Wis +4
**Skills:** Perception +7, Stealth +6

---

### Traits

**Magic Resistance.** The witchstalker has advantage on saving throws against spells and other magical effects.

**Smell Magic.** The witchstalker can sense the presence and location of magic within 120 feet of itself. It also has advantage on attack rolls against creatures that have cast a spell since the end of the witchstalker's last turn.


---

### Actions

**Multiattack.** The witchstalker makes two Bite attacks.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 14 (3d6 + 4) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 15 Strength saving throw or have the prone condition.

**Mind-Wracking Howl (Recharge 5–6).** The witchstalker unleashes a terrible howl, and each creature within 30 feet of it that isn't a Monstrosity must make a DC 13 Wisdom saving throw. On a failed save, a creature takes 24 (7d6) psychic damage and has disadvantage on Constitution saving throws to maintain concentration on spells until the end of its next turn. On a successful save, a creature takes half as much damage only.


---

### Reactions

**Spell Stalk.** Immediately after a creature within 120 feet of the witchstalker casts a spell, the witchstalker magically teleports to an unoccupied space within 5 feet of the creature and can make one Bite attack against the creature.


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