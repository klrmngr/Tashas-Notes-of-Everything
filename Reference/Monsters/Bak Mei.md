---
type: pc
race: "Humanoid (human)"
class:
 - "Bak Mei"
subClass:
 - "CR 13"
cover: "Bak Mei.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/13
  - source/cm
---
###### Bak Mei
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Bak Mei.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (Unarmored Defense) |
> | :FasHeart: HP | 102 (12d8 + 48) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 18 | 18 | 13 | 17 | 16 |
| **Mod** | +0 | +4 | +4 | +1 | +3 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Auran, Common
**Saving Throws:** Str +5, Dex +9, Con +9, Int +6, Wis +8, Cha +8
**Skills:** Acrobatics +9, Athletics +5, Medicine +8, Religion +6, Stealth +9
**Damage Resistances:** poison; thunder
**Condition Immunities:** charmed; frightened; paralyzed

---

### Traits

**Legendary Resistance (2/Day).** If Bak Mei fails a saving throw, he can choose to succeed instead.

**Special Equipment.** Bak Mei carries a staff of striking with 10 charges.

**Unarmored Defense.** While Bak Mei is wearing no armor and wielding no shield, his AC includes his Wisdom modifier.


---

### Actions

**Multiattack.** Bak Mei attacks three times: twice with Thunder Strike and once with his staff of striking.

**Thunder Strike.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 15 (2d10 + 4) thunder damage, and if the target is a creature, it must succeed on a DC 17 Constitution saving throw or be deafened and stunned until the start of Bak Mei's next turn.

**Staff of Striking.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage, or 4 (1d8) bludgeoning damage when used with two hands, and Bak Mei can expend up to 3 of the staff's charges. For each expended charge, the target takes an extra 1d6 force damage.

**Heal Self (Recharges after a Long Rest).** Bak Mei regains 2d8 + 4 hit points, and all levels of exhaustion end on him.


---

### Bonus Actions

**Nimble Escape.** Bak Mei takes the Disengage or Hide action.


---

### Reactions

**Deflect Missile.** In response to being hit by a ranged weapon attack, Bak Mei deflects the missile. The damage he takes from the attack is reduced by 1d10 + 12. If the damage is reduced to 0, Bak Mei catches the missile if it's small enough to hold in one hand and Bak Mei has a hand free.


---

### Legendary Actions

### 

**Crane Dance.** Bak Mei moves up to 20 feet. This movement does not provoke opportunity attacks.

**Thunder Strike (Costs 2 Actions).** Bak Mei uses Thunder Strike.


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