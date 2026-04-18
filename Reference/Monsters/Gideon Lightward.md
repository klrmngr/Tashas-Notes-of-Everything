---
type: pc
race: "Undead"
class:
 - "Gideon Lightward"
subClass:
 - "CR 6"
cover: "Gideon Lightward.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/6
  - source/bgdia
---
###### Gideon Lightward
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Gideon Lightward.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 136 (16d8 + 64) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 18 | 10 | 18 | 13 |
| **Mod** | +4 | +1 | +4 | +0 | +4 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common
**Saving Throws:** Dex +4, Con +7, Wis +7
**Skills:** Insight +7, Religion +6
**Damage Vulnerabilities:** radiant
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** necrotic; poison
**Condition Immunities:** exhaustion; paralyzed; poisoned

---

### Traits

**Regeneration.** Gideon regains 10 hit points at the start of each of his turns. If he takes radiant damage, this trait doesn't function at the start of his next turn. Gideon is destroyed only if he starts his turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** Gideon attacks twice with his fists.

**Fist.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage.

**Withering Gaze.** Gideon targets one creature he can see within 60 feet of him. The target must make a DC 15 Constitution saving throw, taking 22 (4d10) necrotic damage on a failed save, or half as much damage on a successful one.


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