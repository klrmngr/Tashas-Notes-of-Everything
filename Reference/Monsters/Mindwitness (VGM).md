---
type: pc
race: "Aberration"
class:
 - "Mindwitness"
subClass:
 - "CR 5"
cover: "Mindwitness.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/5
  - source/vgm
---
###### Mindwitness
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Mindwitness.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 75 (10d10 + 20) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 14 | 15 | 15 | 10 |
| **Mod** | +0 | +2 | +2 | +2 | +2 | +0 |

**Speed:** 0 ft., fly 20 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 18
**Languages:** Deep Speech, Undercommon, telepathy 600 ft.
**Saving Throws:** Int +5, Wis +5
**Skills:** Perception +8
**Condition Immunities:** prone

---

### Traits

**Telepathic Hub.** When the mindwitness receives a telepathic message, it can telepathically share that message with up to seven other creatures within 600 feet of it that it can see.


---

### Actions

**Multiattack.** The mindwitness makes two attacks: one with its tentacles and one with its bite.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 16 (4d6 + 2) piercing damage.

**Tentacles.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 20 (4d8 + 2) psychic damage. if the target is Large or smaller, it is grappled (escape DC 13) and must succeed on a DC 13 Intelligence saving throw or be stunned until this grapple ends.

**Eye Rays.** The mindwitness shoots three of the following magical eye rays at random (reroll duplicates), choosing one to three targets it can see within 120 feet of it:
- The targeted creature must make a DC 13 Charisma saving throw. On a failed save, the target has disadvantage on attack rolls for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
- The targeted creature must succeed on a DC 13 Wisdom saving throw or be frightened for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
- The target must succeed on a DC 13 Intelligence saving throw or take 27 (6d8) psychic damage.
- The targeted creature must make a DC 13 Dexterity saving throw. On a failed save, the target's speed is halved for 1 minute. In addition, the creature can't take reactions, and it can take either an action or a bonus action on its turn but not both. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
- The targeted creature must succeed on a DC 13 Constitution saving throw or be stunned for 1 minute. The target can repeat the saving throw at the start of each of its turns, ending the effect on itself on a success.
- If the target is a creature, it must make a DC 13 Strength saving throw. On a failed save, the mindwitness moves it up to 30 feet in any direction, and it is restrained by the ray's telekinetic grip until the start of the mindwitness's next turn or until the mindwitness is incapacitated.
- If the target is an object weighing 300 pounds or less that isn't being worn or carried, it is telekinetically moved up to 30 feet in any direction. The mindwitness can also exert fine control on objects with this ray, such as manipulating a simple tool or opening a door or a container.


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