---
type: pc
race: "Humanoid (human, warlock)"
class:
 - "Skylla"
subClass:
 - "CR 2"
cover: "Skylla.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/wbtw
---
###### Skylla
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Skylla.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human, warlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Humanoid (human, warlock) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 11 | 14 | 12 | 15 | 17 |
| **Mod** | -1 | +0 | +2 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Elvish
**Saving Throws:** Wis +4, Cha +5
**Skills:** Deception +5, Intimidation +5, Nature +3, Persuasion +5

---

### Traits

**Special Equipment.** Skylla carries an Eldritch Staff (see appendix A) with 10 charges. The staff regains 1d6 + 4 expended charges daily at dawn. If its last charge is expended, roll a d20; on a 1, the staff is destroyed.


---

### Actions

**Multiattack.** Skylla makes two Eldritch Staff attacks. She can replace one of the attacks with a use of Spellcasting.

**Eldritch Staff.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage, or 4 (1d8) bludgeoning damage when used with two hands, and Skylla can expend up to 3 of the staff's charges, dealing an extra 4 (1d8) lightning damage for each expended charge.


---

### Reactions

**Eldritch Escape.** When Skylla takes damage, she can expend 3 charges of her eldritch staff to turn invisible and teleport, along with any equipment she's wearing or carrying, up to 60 feet to an unoccupied space she can see. She remains invisible until the start of her next turn or until she attacks or casts a spell.


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