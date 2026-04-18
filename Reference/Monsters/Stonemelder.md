---
type: pc
race: "Humanoid (human)"
class:
 - "Stonemelder"
subClass:
 - "CR 4"
cover: "Stonemelder.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/pota
---
###### Stonemelder
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Stonemelder.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (splint armor) |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 10 | 16 | 12 | 11 | 17 |
| **Mod** | +2 | +0 | +3 | +1 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** tremorsense 30 ft., passive Perception 12
**Languages:** Common, Terran
**Skills:** Intimidation +5, Perception +2

---

### Traits

**Death Burst.** When the Stonemelder dies, it turns to stone and explodes in a burst of rock shards, becoming a smoking pile of rubble. Each creature within 10 feet of the exploding Stonemelder must make a DC 14 Dexterity saving throw, taking 11 (2d10) bludgeoning damage on a failed save, or half as much damage on a successful one.


---

### Actions

**Black Earth Rod.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage. The Stonemelder can also expend a spell slot to deal extra damage, dealing 2d8 bludgeoning damage for a 1st level slot, plus an additional 1d8 for each level of the slot above 1st.


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