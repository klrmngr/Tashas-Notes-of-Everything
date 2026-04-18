---
type: pc
race: "Humanoid (goblinoid)"
class:
 - "Hobgoblin Iron Shadow"
subClass:
 - "CR 2"
cover: "Hobgoblin Iron Shadow.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/vgm
---
###### Hobgoblin Iron Shadow
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Hobgoblin Iron Shadow.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (goblinoid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Humanoid (goblinoid) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 15 | 14 | 15 | 11 |
| **Mod** | +2 | +3 | +2 | +2 | +2 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Goblin
**Skills:** Acrobatics +5, Athletics +4, Stealth +5

---

### Traits

**Unarmored Defense.** While the hobgoblin is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.


---

### Actions

**Multiattack.** The hobgoblin makes four attacks, each of which can be an unarmed strike or a dart attack. It can also use Shadow Jaunt once, either before or after one of the attacks.

**Unarmed Strike.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) bludgeoning damage.

**Dart.** Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.

**Shadow Jaunt.** The hobgoblin magically teleports, along with any equipment it is wearing or carrying, up to 30 feet to an unoccupied space it can see. Both the space it is leaving and its destination must be in dim light or darkness.


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