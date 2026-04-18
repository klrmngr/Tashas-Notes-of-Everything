---
type: pc
race: "Humanoid (dragonborn)"
class:
 - "Valetta"
subClass:
 - "CR 2"
cover: "Valetta.png"
campaign:
locations:
tags:
  - race/dragonborn
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/wdh
---
###### Valetta
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Valetta.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dragonborn) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 (chain shirt) |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Humanoid (dragonborn) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 12 | 13 | 16 | 13 |
| **Mod** | +0 | +0 | +1 | +1 | +3 | +1 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Draconic
**Skills:** Medicine +7, Persuasion +3, Religion +5
**Damage Resistances:** lightning

---

### Traits

**Divine Eminence.** As a bonus action, Valetta can expend a spell slot to cause her melee weapon attacks to magically deal an extra 10 (3d6) radiant damage to a target on a hit. This benefit lasts until the end of the turn. If Valetta expends a spell slot of 2nd level or higher, the extra damage increases by 1d6 for each level above 1st.


---

### Actions

**Breathe Weapon.** Valetta can use her action to exhale a 5-foot-wide, 30-foot line of lightning (but can't do this again until she finishes a short or long rest); each creature in the line must make a DC 11 Dexterity saving throw, taking 2d6 lightning damage on a failed save, or half as much damage on a successful one.

**Mace.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage.


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