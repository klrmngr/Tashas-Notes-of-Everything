---
type: pc
race: "Fey (goblinoid)"
class:
 - "Oddlewin"
subClass:
 - "CR 2"
cover: "Oddlewin.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/fey
  - size/small
  - cr/2
  - source/bmt
---
###### Oddlewin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Oddlewin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Fey (goblinoid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 13 (leather armor) |
> | :FasHeart: HP | 21 (6d6) |
> | :FasUserGroup: Race | Fey (goblinoid) |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 10 | 10 | 16 | 15 |
| **Mod** | -1 | +2 | +0 | +0 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Goblin, Sylvan
**Skills:** Performance +4, Stealth +6
**Condition Immunities:** charmed

---

### Traits

**Fortune Teller.** Oddlewin can cast the Augury spell as a ritual, using cards as the material component.

**Nilbogism.** Any creature that attempts to damage Oddlewin must first succeed on a DC 12 Charisma saving throw or have the charmed condition until the end of the creature's next turn. The creature must use its action praising Oddlewin.
Oddlewin can't regain hit points, including through magical healing, except through his Reversal of Fortune reaction.


---

### Actions

**Fool's Scepter.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage.

**Cloud of Cards.** Oddlewin conjures magical cards that slash at the air in a 5-foot cube within 60 feet of Oddlewin until the start of Oddlewin's next turn. A creature that starts its turn in the cube or that enters that area for the first time on a turn takes 10 (4d4) slashing damage.


---

### Bonus Actions

**Nimble Escape.** Oddlewin takes the Disengage or Hide action.


---

### Reactions

**Reversal of Fortune.** In response to another creature dealing damage to Oddlewin, Oddlewin reduces the damage to 0 and regains 9 (2d8) hit points.


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