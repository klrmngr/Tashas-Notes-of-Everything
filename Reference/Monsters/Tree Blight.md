---
type: pc
race: "Plant"
class:
 - "Tree Blight"
subClass:
 - "CR 7"
cover: "Tree Blight.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/huge
  - cr/7
  - source/cos
---
###### Tree Blight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Curse of Strahd
___

> [!infobox|no-t right]
> ![[Tree Blight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Plant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 92 (8d12 + 40) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Curse of Strahd |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 20 | 6 | 10 | 3 |
| **Mod** | +6 | +0 | +5 | -2 | +0 | -4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 10
**Languages:** understands Common and Druidic but doesn't speak
**Condition Immunities:** blinded; deafened

---

### Traits

**False Appearance.** While the blight remains motionless, it is indistinguishable from a dead tree.

**Siege Monster.** The blight deals double damage to objects and structures.


---

### Actions

**Multiattack.** The blight makes one Branch attack and one Grasping Root attack.

**Branch.** Melee Weapon Attack: +9 to hit, reach 15 ft., one target. *Hit:* 16 (3d6 + 6) bludgeoning damage.

**Grasping Root.** Melee Weapon Attack: +9 to hit, reach 15 ft., one creature not grappled by the blight. *Hit:* The target is grappled (escape DC 15). Until the grapple ends, the target takes 9 (1d6 + 6) bludgeoning damage at the start of each of its turns. The root has AC 15 and can be severed by dealing 6 slashing damage or more to it at once. Cutting the root doesn't hurt the blight, but ends the grapple.


---

### Bonus Actions

**Bite.** Melee Weapon Attack: +9 to hit, reach 5 ft., one creature grappled by the blight. *Hit:* 19 (3d8 + 6) piercing damage.


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