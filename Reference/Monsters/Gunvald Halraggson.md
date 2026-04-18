---
type: pc
race: "Humanoid (human)"
class:
 - "Gunvald Halraggson"
subClass:
 - "CR 5"
cover: "Gunvald Halraggson.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/idrotf
---
###### Gunvald Halraggson
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Gunvald Halraggson.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 (hide armor, shield) |
> | :FasHeart: HP | 76 (9d8 + 36) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 8 | 18 | 9 | 10 | 16 |
| **Mod** | +5 | -1 | +4 | -1 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common
**Skills:** Athletics +8, Intimidation +6, Survival +3

---

### Traits

**Indomitable (3/Day).** Gunvald can reroll a saving throw he fails. He must use the new roll.

**Menacing Blows (1/Turn).** Gunvald deals an extra 6 (1d12) damage when he hits a target with a weapon attack. If the target is a creature, it must succeed on a DC 14 Wisdom saving throw or be frightened until the start of Gunvald's next turn.

**Second Wind (Recharges after a Short or Long Rest).** As a bonus action, Gunvald can regain 15 hit points.


---

### Actions

**Multiattack.** Gunvald makes three melee attacks.

**Battleaxe.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) slashing damage, or 10 (1d10 + 5) slashing damage when used with two hands, plus 6 (1d12) slashing damage if Gunvald uses Menacing Blows.

**Javelin.** Melee or Ranged Weapon Attack: +8 to hit, range 30/120 ft., one target. *Hit:* 8 (1d6 + 5) piercing damage, plus 6 (1d12) piercing damage if Gunvald uses Menacing Blows.


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