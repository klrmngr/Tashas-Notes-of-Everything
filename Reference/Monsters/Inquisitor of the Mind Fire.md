---
type: pc
race: "Humanoid"
class:
 - "Inquisitor of the Mind Fire"
subClass:
 - "CR 8"
cover: "Inquisitor of the Mind Fire.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/vrgr
---
###### Inquisitor of the Mind Fire
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Inquisitor of the Mind Fire.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 77 (14d8 + 14) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 17 | 16 | 19 |
| **Mod** | +0 | +2 | +1 | +3 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 30 ft., passive Perception 16
**Languages:** any three languages, telepathy 120 ft.
**Saving Throws:** Int +6, Wis +6, Cha +7
**Skills:** Insight +6, Perception +6
**Condition Immunities:** charmed; frightened

---

### Actions

**Multiattack.** The inquisitor attacks twice with its Silver Longsword or uses Mind Fire twice.

**Silver Longsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) if used with two hands, plus 18 (4d8) force damage.

**Mind Fire.** The inquisitor targets one creature it can see within 120 feet of it. The target must succeed on a DC 15 Intelligence saving throw or take 17 (3d8 + 4) psychic damage and be stunned until the start of the inquisitor's next turn.

**Inquisitor's Command (Recharge 5–6).** Each creature of the inquisitor's choice that it can see within 60 feet of it must succeed on a DC 15 Wisdom saving throw or be charmed until the start of the inquisitor's next turn. On the charmed target's turn, the inquisitor can telepathically control the target's move, action, or both. When controlled in this way, the target can take only the Attack (inquisitor chooses the target) or Dash action.


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