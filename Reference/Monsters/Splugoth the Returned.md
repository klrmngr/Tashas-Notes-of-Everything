---
type: pc
race: "Humanoid (goblinoid)"
class:
 - "Splugoth the Returned"
subClass:
 - "CR 2"
cover: "Splugoth the Returned.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/ai
---
###### Splugoth the Returned
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Acquisitions Incorporated
___

> [!infobox|no-t right]
> ![[Splugoth the Returned.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid (goblinoid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 27 (6d6 + 6) |
> | :FasUserGroup: Race | Humanoid (goblinoid) |
> | :FasBook: Source | Acquisitions Incorporated |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 14 | 11 | 10 |
| **Mod** | +0 | +2 | +1 | +2 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Draconic, Elvish, Goblin
**Saving Throws:** Int +4, Wis +2
**Skills:** Stealth +6

---

### Traits

**Defensive Advantage.** As long as two or more of Splugoth's allies are within 5 feet of him and are not incapacitated, attack rolls against him are made with disadvantage.

**Nimble Escape.** Splugoth can take the Disengage or Hide action as a bonus action on each of his turns.

**Touch of Madness.** Splugoth has advantage on saving throws against being charmed or frightened.


---

### Actions

**Multiattack.** Splugoth makes two attacks with his dagger.

**Dagger.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) slashing damage.

**Word From Beyond (1/Day).** Splugoth remembers and repeats aloud a few words from a place he entered while walking back from the next world to this one. Each creature of his choice within 30 feet of him that can hear him must succeed on a DC 12 Wisdom saving throw or be stunned until the end of its next turn.


---

### Reactions

**Absorb Attack.** When a creature Splugoth can see hits him with a melee weapon attack, the weapon snags on a pocket of residual resurrectional energy and is caught fast. The attack is negated and the weapon cannot be used until the creature succeeds on a DC 12 Strength (Athletics) check as an action to pull it out of Splugoth. Natural weapons can have their attacks negated by this feature, but can then be retracted automatically at the end of the attacking creature's turn.


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