---
type: pc
race: "Humanoid (gnoll)"
class:
 - "Daask Bruiser"
subClass:
 - "CR 9"
cover: "Daask Bruiser.png"
campaign:
locations:
tags:
  - race/gnoll
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/efa
---
###### Daask Bruiser
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Daask Bruiser.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (gnoll) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 150 (20d8 + 60) |
> | :FasUserGroup: Race | Humanoid (gnoll) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 13 | 16 | 10 | 12 | 14 |
| **Mod** | +5 | +1 | +3 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 15
**Languages:** Common, Gnoll
**Saving Throws:** Str +9, Con +7, Wis +5
**Skills:** Athletics +9, Intimidation +6, Perception +5

---

### Traits

**Blood Frenzy.** The bruiser has Advantage on attack rolls against any creature that doesn't have all its Hit Points.


---

### Actions

**Multiattack.** The bruiser makes three Pummel attacks and uses Glare.

**Pummel.** m +9, reach 5 ft. *Hit:* 12 (2d6 + 5) Bludgeoning damage.

**Glare.** wis DC 14, one creature the bruiser can see within 30 feet.  The target has the Frightened condition until the start of the bruiser's next turn.


---

### Reactions

**Smackback.**  The bruiser takes damage from a creature within 5 feet.  The bruiser makes one Pummel attack, targeting the triggering creature.


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