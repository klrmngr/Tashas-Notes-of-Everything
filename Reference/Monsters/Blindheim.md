---
type: pc
race: "Humanoid (blindheim)"
class:
 - "Blindheim"
subClass:
 - "CR 2"
cover: "Blindheim.png"
campaign:
locations:
tags:
  - race/blindheim
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/mff
---
###### Blindheim
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MFF
___

> [!infobox|no-t right]
> ![[Blindheim.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (blindheim) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 26 (4d8 + 8) |
> | :FasUserGroup: Race | Humanoid (blindheim) |
> | :FasBook: Source | MFF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 15 | 8 | 10 | 9 |
| **Mod** | +1 | +3 | +2 | -1 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Undercommon
**Skills:** Athletics +3, Perception +2

---

### Traits

**Radiant Eyes.** While its eyes are open, a blindheim projects bright light in a 60-foot cone and dim light for an additional 60 feet. It sets the orientation of this cone at the end of each of its turns. All creatures that can see the blindheim have disadvantage on attack rolls while in the area of bright light and within 15 feet of the blindheim. Creatures with the Sunlight Sensitivity trait that can see the blindheim have disadvantage on attack rolls anywhere in the area of bright light.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6 + 2) piercing damage.

**Radiant Blast.** Radiant energy erupts from the blindheim's eyes in a 15-foot cone. Each creature in that area must succeed on a DC 12 Constitution saving throw or take 7 (2d6) radiant damage and be blinded until the end of the blindheim's next turn. Creatures with the Sunlight Sensitivity trait have disadvantage on this saving throw.


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