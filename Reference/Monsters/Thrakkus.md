---
type: pc
race: "Humanoid (dragonborn)"
class:
 - "Thrakkus"
subClass:
 - "CR 2"
cover: "Thrakkus.png"
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
###### Thrakkus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Thrakkus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dragonborn) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (hide armor) |
> | :FasHeart: HP | 67 (9d8 + 27) |
> | :FasUserGroup: Race | Humanoid (dragonborn) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 17 | 9 | 11 | 9 |
| **Mod** | +3 | +1 | +3 | -1 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Draconic
**Damage Resistances:** fire

---

### Traits

**Reckless.** At the start of his turn, Thrakkus can gain advantage on all melee weapon attack rolls during that turn, but attack rolls against him have advantage until the start of his next turn.


---

### Actions

**Greataxe.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 9 (1d12 + 3) slashing damage.

**Breath Weapon (1/Day).** Thrakkus can use his action to exhale a 15-foot cone of fire. Each creature in the cone must make a DC 13 Dexterity saving throw, taking 6 (2d6) fire damage on a failed save, or half as much damage on a successful one.


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