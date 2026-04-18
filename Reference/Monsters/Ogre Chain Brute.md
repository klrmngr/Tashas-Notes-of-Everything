---
type: pc
race: "Giant"
class:
 - "Ogre Chain Brute"
subClass:
 - "CR 3"
cover: "Ogre Chain Brute.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/large
  - cr/3
  - source/mpmm
---
###### Ogre Chain Brute
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Ogre Chain Brute.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Giant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 11 (hide armor) |
> | :FasHeart: HP | 59 (7d10 + 21) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 8 | 16 | 5 | 7 | 7 |
| **Mod** | +4 | -1 | +3 | -3 | -2 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** Common, Giant

---

### Actions

**Fist.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (2d4 + 4) bludgeoning damage.

**Chain Smash (Recharge 6).** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage, and the target must make a DC 14 Constitution saving throw or be stunned for 1 minute. The target repeats the saving throw if it takes damage and at the end of each of its turns, ending the effect on itself on a success.

**Chain Sweep.** The ogre swings its chain, and every creature within 10 feet of it must make a DC 14 Dexterity saving throw. On a failed saving throw, a creature takes 8 (1d8 + 4) bludgeoning damage and is knocked prone. On a successful save, the creature takes half as much damage and isn't knocked prone.


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