---
type: pc
race: "Giant (druid)"
class:
 - "Ogre Chitterlord"
subClass:
 - "CR 3"
cover: "Ogre Chitterlord.png"
campaign:
locations:
tags:
  - race/druid
  - affinity/hostile
  - type/giant
  - size/large
  - cr/3
  - source/mcv4ec
---
###### Ogre Chitterlord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Ogre Chitterlord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Giant (druid) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 (hide armor) |
> | :FasHeart: HP | 52 (7d10 + 14) |
> | :FasUserGroup: Race | Giant (druid) |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 15 | 5 | 12 | 9 |
| **Mod** | +4 | +0 | +2 | -3 | +1 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Giant
**Saving Throws:** Wis +3
**Skills:** Animal Handling +3, Nature +1

---

### Traits

**Speak with Rats.** The ogre can verbally communicate simple concepts to ordinary rats and giant rats.


---

### Actions

**Multiattack.** The ogre makes two Club attacks, two Rat-Tail Whip attacks, or one of each.

**Club.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 15 (2d10 + 4) bludgeoning damage.

**Rat-Tail Whip.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage, and if the target is Large or smaller, it is pulled 5 feet toward the ogre.


---

### Bonus Actions

**Call Rats (1/Day).** The ogre magically calls 1d4 giant rats. Each rat appears in an unoccupied space within 30 feet of the ogre that the ogre can see. The rats act as the ogre's allies, obey its spoken commands, and take their turns immediately after the ogre's turn on the same initiative count. The rats remain for 1 hour, until the ogre dies, or until the ogre dismisses them as a bonus action.


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