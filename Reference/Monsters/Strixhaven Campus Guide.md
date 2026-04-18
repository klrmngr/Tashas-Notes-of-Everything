---
type: pc
race: "Construct"
class:
 - "Strixhaven Campus Guide"
subClass:
 - "CR 1"
cover: "Strixhaven Campus Guide.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/small
  - cr/1
  - source/scc
---
###### Strixhaven Campus Guide
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Strixhaven Campus Guide.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Construct |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 31 (7d6 + 7) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 13 | 10 | 12 | 12 |
| **Mod** | +2 | +2 | +1 | +0 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 11
**Languages:** Common plus any three languages
**Saving Throws:** Dex +4
**Skills:** Insight +3, Persuasion +3
**Damage Immunities:** poison
**Condition Immunities:** blinded; deafened; exhaustion; paralyzed; petrified; poisoned

---

### Traits

**Campus Knowledge.** While at Strixhaven, the guide can't become lost by magical or nonmagical means. The guide also has advantage on ability checks made to locate creatures or objects at Strixhaven.

**Univocal Speech.** When the guide speaks, any creature that knows at least one language and can hear the guide understands what it says.

**Unusual Nature.** The guide doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The guide makes two Slam attacks.

**Slam.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) bludgeoning damage.

**Smile and Wave.** Each creature of the guide's choice that is within 30 feet of the guide must succeed on a DC 11 Wisdom saving throw or be magically charmed by the guide for 1 hour.
A charmed target must move on its turn toward the guide, trying to get within 5 feet of the guide. The target doesn't move into obviously dangerous ground, such as a fire or a pit. Whenever the charmed target takes damage, it can repeat the saving throw, ending the effect on itself on a success.
A target that successfully saves is immune to any guide's Smile and Wave ability for the next 24 hours.


---

### Bonus Actions

**Need Directions.** The guide takes the Help action.


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