---
type: pc
race: "Humanoid (goblinoid)"
class:
 - "Norker War Leader"
subClass:
 - "CR 3"
cover: "Norker War Leader.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/3
  - source/mff
---
###### Norker War Leader
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MFF
___

> [!infobox|no-t right]
> ![[Norker War Leader.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Humanoid (goblinoid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Humanoid (goblinoid) |
> | :FasBook: Source | MFF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 15 | 12 | 11 | 13 |
| **Mod** | +3 | +0 | +2 | +1 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Goblin
**Skills:** Athletics +5, Intimidation +3, Perception +2

---

### Actions

**Multiattack.** The norker war leader makes one greataxe and one bite attack, and also uses Fight On, You Slugs.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

**Greataxe.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 9 (1d12 + 3) slashing damage.

**Fight On, You Slugs.** The norker war leader picks up to three allied goblinoids within 60 feet that can see it. The chosen creatures can each use their reactions to make a single melee attack.


---

### Reactions

**Defensive Rebuke.** If a creature within 5 feet of the norker makes a melee attack against it, the norker can use its reaction to cause 6 piercing damage to it.


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