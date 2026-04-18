---
type: pc
race: "Fey (goblinoid)"
class:
 - "Nilbog"
subClass:
 - "CR 1"
cover: "Nilbog.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/fey
  - size/small
  - cr/1
  - source/mpmm
---
###### Nilbog
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Nilbog.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Fey (goblinoid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 13 (leather armor) |
> | :FasHeart: HP | 7 (2d6) |
> | :FasUserGroup: Race | Fey (goblinoid) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 10 | 10 | 8 | 15 |
| **Mod** | -1 | +2 | +0 | +0 | -1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** Common, Goblin
**Skills:** Stealth +6

---

### Traits

**Nilbogism.** Any creature that attempts to damage the nilbog must first succeed on a DC 12 Charisma saving throw or be charmed until the end of the creature's next turn. A creature charmed in this way must use its action praising the nilbog.
The nilbog can't regain hit points, including through magical healing, except through its Reversal of Fortune reaction.


---

### Actions

**Fool's Scepter.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage.

**Mocking Word.** The nilbog targets one creature it can see within 60 feet of it. The target must succeed on a DC 12 Wisdom saving throw or take 5 (2d4) psychic damage and have disadvantage on its next attack roll before the end of its next turn.


---

### Bonus Actions

**Nimble Escape.** The nilbog takes the Disengage or Hide action.


---

### Reactions

**Reversal of Fortune.** In response to another creature dealing damage to the nilbog, the nilbog reduces the damage to 0 and regains 3 (1d6) hit points.


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