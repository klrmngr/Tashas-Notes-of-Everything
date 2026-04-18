---
type: pc
race: "Humanoid (human)"
class:
 - "Jade Tigress"
subClass:
 - "CR 8"
cover: "Jade Tigress.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/cm
---
###### Jade Tigress
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Jade Tigress.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (Unarmored Defense) |
> | :FasHeart: HP | 71 (11d8 + 21) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 15 | 11 | 16 | 11 |
| **Mod** | +4 | +2 | +2 | +0 | +3 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common
**Saving Throws:** Str +7, Con +5
**Skills:** Athletics +7, Insight +6, Intimidation +3, Perception +6
**Damage Resistances:** poison
**Condition Immunities:** charmed; frightened

---

### Traits

**Unarmored Defense.** While Jade Tigress is wearing no armor and wielding no shield, her AC includes her Wisdom modifier.


---

### Actions

**Multiattack.** Jade Tigress makes three attacks.

**Force Strike.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) force damage, and if the target is a creature, it must succeed on a DC 15 Constitution saving throw or be stunned until the end of Jade Tigress's next turn.

**Poisoned Dart.** Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage plus 7 (3d4) poison damage, and the target must succeed on a DC 15 Constitution saving throw or gain 1 level of exhaustion.

**Heal Self (Recharges after a Long Rest).** Jade Tigress regains 2d8 + 2 hit points, and all levels of exhaustion end on her.


---

### Bonus Actions

**Nimble Escape.** Jade Tigress takes the Disengage or Hide action.


---

### Reactions

**Deflect Missile.** In response to being hit by a ranged weapon attack, Jade Tigress deflects the missile. The damage she takes from the attack is reduced by 1d10 + 9. If the damage is reduced to 0, Jade Tigress catches the missile if it's small enough to hold in one hand and Jade Tigress has a hand free.


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