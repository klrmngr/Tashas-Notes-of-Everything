---
type: pc
race: "Humanoid"
class:
 - "Koh Tam"
subClass:
 - "CR 10"
cover: "Koh Tam.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/10
  - source/coa
---
###### Koh Tam
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Koh Tam.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 17 (breastplate, shield) |
> | :FasHeart: HP | 143 (22d8 + 44) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 15 | 19 | 20 | 15 |
| **Mod** | +3 | +1 | +2 | +4 | +5 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Abyssal, Celestial, Common, Infernal
**Saving Throws:** Wis +9, Cha +6
**Skills:** Arcana +8, History +8, Insight +9, Religion +8

---

### Actions

**Arbiter's Touch.** Melee Spell Attack: +9 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) radiant damage.

**Judgement.** Koh Tam judges a creature within 60 feet of him. The target must succeed on a DC 17 Wisdom saving throw or take 50 (10d8 + 5) radiant damage. If the target had fewer hit points than their maximum prior to this attack, the creature takes 70 (10d12 + 5) radiant damage instead.

**Arbiter's Light (Recharge 4–6).** Ranged Spell Attack: +9 to hit, range 120 ft., one target. *Hit:* 70 (10d12 + 5) radiant damage, and the target has the blinded condition until the start of Koh Tam's next turn.


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