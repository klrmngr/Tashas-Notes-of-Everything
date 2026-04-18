---
type: pc
race: "Humanoid (bard, tiefling)"
class:
 - "Windfall"
subClass:
 - "CR 23"
cover: "Windfall.png"
campaign:
locations:
tags:
  - race/bard
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/23
  - source/veor
---
###### Windfall
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Windfall.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (bard, tiefling) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 (studded leather armor) |
> | :FasHeart: HP | 323 (34d8 + 170) |
> | :FasUserGroup: Race | Humanoid (bard, tiefling) |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 24 | 20 | 22 | 18 | 26 |
| **Mod** | +2 | +7 | +5 | +6 | +4 | +8 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 21
**Languages:** Common, Draconic, Infernal
**Saving Throws:** Str +9, Dex +14, Wis +11, Cha +15
**Skills:** Arcana +13, Deception +22, Insight +18, Perception +11, Performance +22, Persuasion +22, Sleight Of Hand +14
**Damage Resistances:** acid; cold; fire; lightning; thunder
**Condition Immunities:** charmed; frightened

---

### Traits

**Dazzling Visage.** A brilliant array of chromatic colors emanates from Windfall, causing attack rolls against her to have disadvantage. This trait ceases to function while Windfall has the incapacitated condition or has a speed of 0.

**Legendary Resistance (3/Day).** If Windfall fails a saving throw, she can choose to succeed instead.

**Special Equipment.** Windfall wears an iridescent magic coat that was tailored specifically for her and imbued with Tiamat's power. When she dies, the coat functions as a Robe of Scintillating Colors.


---

### Actions

**Multiattack.** Windfall makes two Chromatic Rapier attacks and uses Dragon's Fury once.

**Chromatic Rapier.** Melee Weapon Attack: +14 to hit, reach 5 ft., one target. *Hit:* 11 (1d8 + 7) piercing damage plus 21 (6d6) acid, cold, fire, lightning, or poison damage (Windfall's choice).

**Dragon's Fury.** Windfall targets one creature she can see within 60 feet of herself and unleashes a burst of magical ire. The target must make a DC 23 Wisdom saving throw. On a failed save, the target takes 36 (8d8) psychic damage and has the frightened condition until the start of Windfall's next turn. On a successful save, the target takes half as much damage only.


---

### Bonus Actions

**Stunning Scintillation (Recharge 5–6).** Windfall emits an overwhelming array of colors from her coat. Each creature within 30 feet of Windfall that can see her must succeed on a DC 23 Constitution saving throw or have the stunned condition until the start of Windfall's next turn.


---

### Legendary Actions

### 

**Deft Dance.** Windfall moves up to her speed without provoking opportunity attacks.

**Dragon's Flare.** Windfall flares with multicolored flames and targets a creature she can see within 30 feet of herself. The target must make a DC 23 Dexterity saving throw. On a failed save, the target takes 26 (4d12) damage of a type chosen by Windfall: acid, cold, fire, lightning, or poison. On a successful save, the target takes half as much damage.

**Cast a Spell (Costs 2 Actions).** Windfall uses Spellcasting.


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