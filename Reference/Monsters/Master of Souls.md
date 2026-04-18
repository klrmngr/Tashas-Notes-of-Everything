---
type: pc
race: "Humanoid (human)"
class:
 - "Master of Souls"
subClass:
 - "CR 4"
cover: "Master of Souls.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/bgdia
---
###### Master of Souls
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Master of Souls.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 17 | 19 | 14 | 13 |
| **Mod** | +0 | +2 | +3 | +4 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Abyssal, Common, Infernal
**Saving Throws:** Wis +4
**Skills:** Arcana +6, Religion +6

---

### Traits

**Grave Magic.** When the master of souls cast a spell that deals damage, it can change the spell's damage type to necrotic.


---

### Actions

**Multiattack.** The master of souls attacks twice with its flail.

**Silvered Skull Flail.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 4 (1d8) bludgeoning damage plus 14 (4d6) necrotic damage, and the target has disadvantage on all saving throws until the end of the master of souls' next turn.

**Chill Touch (Cantrip).** Ranged Spell Attack: +6 to hit, range 120 ft., one creature. *Hit:* 13 (2d8) necrotic damage, and the target can't regain hit points until the start of the master of souls' next turn. If the target is undead, it has disadvantage on attack rolls against the master of souls for the same duration.

**Ray of Sickness (1st-Level Spell; Requires a Spell Slot).** Ranged Spell Attack: +6 to hit, range 60 ft., one creature. *Hit:* 9 (2d8) poison damage, and the target must succeed on a DC 14 Constitution saving throw or be poisoned until the end of the master of souls' next turn. If the master of souls casts this spell using a spell slot of 2nd level or higher, the damage increases by 1d8 for each slot level above 1st.

**Scorching Ray (2nd-Level Spell; Requires a Spell Slot).** Ranged Spell Attack: +6 to hit, range 120 ft., one target per ray (3 rays if a 2nd-level spell slot is used, 4 rays if a 3rd-level spell slot is used). *Hit:* 7 (2d6) fire damage per ray.


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