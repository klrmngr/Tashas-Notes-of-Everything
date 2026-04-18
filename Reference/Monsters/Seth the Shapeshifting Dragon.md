---
type: pc
race: "Dragon"
class:
 - "Seth the Shapeshifting Dragon"
subClass:
 - "CR 10"
cover: "Seth the Shapeshifting Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/10
  - source/mismv1
---
###### Seth the Shapeshifting Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MisMV1
___

> [!infobox|no-t right]
> ![[Seth the Shapeshifting Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Dragon |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 153 (18d8 + 72) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | MisMV1 |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 25 | 19 | 13 | 15 | 14 |
| **Mod** | +3 | +7 | +4 | +1 | +2 | +2 |

**Speed:** 50 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 16
**Languages:** Aquan, Common, Draconic
**Saving Throws:** Str +7, Dex +11, Con +8
**Skills:** Perception +6, Stealth +11
**Damage Resistances:** cold; fire
**Damage Immunities:** poison
**Condition Immunities:** grappled; poisoned; restrained

---

### Traits

**Amphibious.** Seth can breathe air and water.

**Invisible in Water.** Seth has the invisible condition while fully immersed in water.


---

### Actions

**Multiattack.** Seth makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 10 (1d6 + 7) piercing damage plus 9 (2d8) cold damage.

**Claw.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 14 (2d6 + 7) slashing damage.

**Riptide Breath (Recharge 5–6).** Seth exhales a torrent of frigid water in a 30-foot cone. Each creature in that area must make a DC 16 Constitution saving throw. On a failed save, the creature takes 36 (8d8) cold damage and has the incapacitated condition until the end of its next turn. On a successful save, the creature takes half as much damage only.


---

### Bonus Actions

**Change Shape.** Seth magically transforms into a Small Humanoid or a Beast that is Tiny or Small, while retaining his game statistics (other than his size). This transformation ends if Seth is reduced to 0 hit points or uses another bonus action to end it.

**Superspeed (2/Day).** Seth's speed is doubled for as long as he maintains concentration (as if concentrating on a spell). While his speed is increased in this way, all attack rolls against him are made with disadvantage, and he becomes partially incorporeal, allowing him to move through creatures and objects as if they were difficult terrain. Seth takes 5 (1d10) force damage if he ends his turn inside an object.


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