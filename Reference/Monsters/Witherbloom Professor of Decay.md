---
type: pc
race: "Humanoid (druid)"
class:
 - "Witherbloom Professor of Decay"
subClass:
 - "CR 7"
cover: "Witherbloom Professor of Decay.png"
campaign:
locations:
tags:
  - race/druid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/7
  - source/scc
---
###### Witherbloom Professor of Decay
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Witherbloom Professor of Decay.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Small Humanoid (druid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 (hide armor) |
> | :FasHeart: HP | 105 (14d8 + 42) |
> | :FasUserGroup: Race | Humanoid (druid) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 16 | 16 | 19 | 13 |
| **Mod** | +0 | +2 | +3 | +3 | +4 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common plus any four languages
**Saving Throws:** Con +6, Int +6, Wis +7, Cha +4
**Skills:** Arcana +6, Medicine +7, Nature +6, Survival +7
**Damage Resistances:** necrotic

---

### Traits

**Essence Transfer (1/Day).** The professor can cast the animate dead spell, using Wisdom as the spellcasting ability.


---

### Actions

**Multiattack.** The professor makes two Mortality Spear attacks. It can replace one of the attacks with a use of Spellcasting.

**Mortality Spear.** Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 17 (3d8 + 4) necrotic damage, and the target can't regain hit points until the start of the professor's next turn.

**Essence Pulse (Recharge 5–6).** The professor creates a life-draining vortex in a 30-foot-radius sphere centered on itself. Each creature of the professor's choice that it can see within that area must make a DC 15 Constitution saving throw, taking 23 (5d8) necrotic damage on a failed save, or half as much damage on a successful one. The professor then regains 10 hit points. An affected creature's hit point maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the creature finishes a long rest. The creature dies if its hit point maximum is reduced to 0.


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