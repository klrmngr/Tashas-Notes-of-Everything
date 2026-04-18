---
type: pc
race: "Giant (sorcerer)"
class:
 - "Irda Veil Keeper"
subClass:
 - "CR 4"
cover: "Irda Veil Keeper.png"
campaign:
locations:
tags:
  - race/sorcerer
  - affinity/hostile
  - type/giant
  - size/medium
  - cr/4
  - source/mcv2dc
---
###### Irda Veil Keeper
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV2DC
___

> [!infobox|no-t right]
> ![[Irda Veil Keeper.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Giant (sorcerer) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 49 (9d8 + 9) |
> | :FasUserGroup: Race | Giant (sorcerer) |
> | :FasBook: Source | MCV2DC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 16 | 13 | 14 | 17 | 19 |
| **Mod** | -1 | +3 | +1 | +2 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., truesight 5 ft., passive Perception 17
**Languages:** Common, Giant, Sylvan
**Saving Throws:** Int +4, Wis +5, Cha +6
**Skills:** Arcana +4, Insight +7, Perception +7
**Condition Immunities:** charmed; frightened

---

### Actions

**Multiattack.** The veil keeper uses Augment Physicality, if available, and makes two Mirage Flare attacks.

**Mirage Flare.** Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 11 (2d6 + 4) radiant damage, and the target must succeed on a DC 14 Wisdom saving throw or be charmed by the veil keeper until the start of the veil keeper's next turn. While charmed in this way, a creature is incapacitated as it is beset by hypnotic, illusory visions.

**Augment Physicality (1/Day).** For 1 minute, the veil keeper magically obscures it location, heightens its physical ability, and increases in size, along with anything it is wearing or carrying. While the veil keeper is augmented, attack rolls against it have disadvantage, it is Large, and it makes Strength and Dexterity saving throws with advantage. If the veil keeper lacks the room to become Large, it attains the maximum size possible in the space available. These augmentations end if the veil keeper is incapacitated.

**Change Shape (3/Day).** The veil keeper magically transforms to look and feel like a Medium Humanoid it has seen. Any equipment the veil keeper is wearing or carrying isn't transformed, and the veil keeper's statistics don't change. The veil keeper reverts to its true form if the veil keeper is reduced to 0 hit points or if the veil keeper uses an action to end the transformation.


---

### Reactions

**Obscuring Mist.** If a creature that the veil keeper can see within 30 feet of itself is targeted by an attack, the veil keeper surrounds the creature with illusory mist, granting the creature 3 until the start of the veil keeper's next turn.


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