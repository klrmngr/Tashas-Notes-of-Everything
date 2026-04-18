---
type: pc
race: "Dragon (sorcerer)"
class:
 - "Galazeth Prismari"
subClass:
 - "CR 23"
cover: "Galazeth Prismari.png"
campaign:
locations:
tags:
  - race/sorcerer
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/23
  - source/scc
---
###### Galazeth Prismari
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Galazeth Prismari.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (sorcerer) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 402 (23d20 + 161) |
> | :FasUserGroup: Race | Dragon (sorcerer) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 14 | 25 | 18 | 20 | 26 |
| **Mod** | +8 | +2 | +7 | +4 | +5 | +8 |

**Speed:** 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 22
**Languages:** Common, Draconic
**Saving Throws:** Dex +9, Con +14, Wis +12, Cha +15
**Skills:** Acrobatics +16, Arcana +18, Perception +12, Performance +22
**Damage Resistances:** lightning
**Damage Immunities:** cold; fire

---

### Traits

**Legendary Resistance (3/Day).** If Galazeth fails a saving throw, he can choose to succeed instead.


---

### Actions

**Multiattack.** Galazeth makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +15 to hit, reach 15 ft., one target. *Hit:* 13 (1d10 + 8) piercing damage plus 5 (1d10) lightning damage.

**Claw.** Melee Weapon Attack: +15 to hit, reach 10 ft., one target. *Hit:* 11 (1d6 + 8) slashing damage. If the target is a Large or smaller creature, it is knocked prone.

**Dancing Elements Breath (Recharge 5–6).** Galazeth exhales a blast of flames and ice in a 90-foot cone. Each creature in that area must make a DC 22 Dexterity saving throw, gaining no benefit from cover (other than 3) and taking 38 (7d10) fire damage and 38 (7d10) cold damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Claw.** Galazeth makes one Claw attack.

**Lightning Flash (Costs 2 Actions).** Galazeth moves up to half his flying speed without provoking opportunity attacks. When he passes within 15 feet of a creature during this move, that creature must succeed on a DC 22 Dexterity saving throw or take 11 (2d10) lightning damage. A creature can take this damage no more than once during the move.

**Flowing Creation (Costs 3 Actions).** Galazeth magically summons 1d4 [[Art Elemental Mascot|elemental mascots]] in unoccupied spaces he can see within 60 feet of himself. The art elementals obey his commands and take their turns immediately after his. Any creature, other than an art elemental, takes 5 (1d10) cold, fire, or lightning damage (Galazeth's choice) if it ends its turn within 5 feet of one or more of these elementals. When one of these elementals drops to 0 hit points, Galazeth can fly up to 20 feet without provoking opportunity attacks. These elementals disappear after 10 minutes, when Galazeth dies, or when he uses this action again.


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