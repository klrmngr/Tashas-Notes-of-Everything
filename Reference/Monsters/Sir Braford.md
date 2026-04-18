---
type: pc
race: "Humanoid (human)"
class:
 - "Sir Braford"
subClass:
 - "CR 1/2"
cover: "Sir Braford.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/tftyp
---
###### Sir Braford
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Sir Braford.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (chain mail, shield) |
> | :FasHeart: HP | 19 (3d8 + 6) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 9 | 14 | 10 | 13 | 14 |
| **Mod** | +3 | -1 | +2 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common
**Skills:** Athletics +5, Perception +3

---

### Traits

**Barkskin.** Sir Braford's AC can't be lower than 16.

**Special Equipment.** Sir Braford wields Shatterspike, a magic longsword that grants a +1 bonus to attack and damage rolls made with it (included in his attack). See the Shatterspike handout for the item's other properties.

**Tree Thrall.** If the Gulthias Tree dies, Sir Braford dies 24 hours later.


---

### Actions

**Longsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands.


---

### Reactions

**Protection.** When a creature Sir Braford can see attacks a target other than him that is within 5 feet of him, he can use a reaction to use his shield to impose disadvantage on the attack roll.


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