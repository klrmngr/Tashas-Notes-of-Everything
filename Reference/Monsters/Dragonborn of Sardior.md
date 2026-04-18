---
type: pc
race: "Humanoid"
class:
 - "Dragonborn of Sardior"
subClass:
 - "CR 6"
cover: "Dragonborn of Sardior.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/6
  - source/ftd
---
###### Dragonborn of Sardior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Dragonborn of Sardior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 (mental defense) |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 17 | 18 | 14 | 12 |
| **Mod** | +2 | +3 | +3 | +4 | +2 | +1 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Draconic
**Saving Throws:** Con +6, Int +7, Wis +5, Cha +4
**Skills:** Arcana +7, History +7, Perception +5
**Damage Resistances:** psychic
**Condition Immunities:** frightened

---

### Traits

**Legendary Resistance (1/Day).** If the dragonborn fails a saving throw, it can choose to succeed instead.

**Mental Defense.** While the dragonborn is wearing no armor, its AC includes its Intelligence modifier.


---

### Actions

**Multiattack.** The dragonborn makes three Mind Blade attacks.

**Mind Blade.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage plus 10 (3d6) psychic damage.

**Heat Breath (Recharge 6).** The dragonborn exhales a wave of intense heat in a 30-foot cone. Each creature in that area must make a DC 14 Constitution saving throw, taking 27 (6d8) fire damage on a failed save, or half as much damage on a successful one. Metal objects in that area glow red-hot until the end of the dragonborn's next turn. Any creature in physical contact with a heated object at the start of its turn must make a DC 14 Constitution saving throw. On a failed save, the creature takes 9 (2d8) fire damage and has disadvantage on attack rolls until the start of its next turn.


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