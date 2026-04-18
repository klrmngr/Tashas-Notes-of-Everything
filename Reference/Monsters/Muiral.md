---
type: pc
race: "Monstrosity"
class:
 - "Muiral"
subClass:
 - "CR 13"
cover: "Muiral.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/13
  - source/wdmm
---
###### Muiral
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDMM
___

> [!infobox|no-t right]
> ![[Muiral.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 195 (23d10 + 69) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | WDMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 11 | 16 | 18 | 13 | 18 |
| **Mod** | +4 | +0 | +3 | +4 | +1 | +4 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Common, Dwarvish, Elvish, Goblin, Undercommon
**Saving Throws:** Con +8, Int +9
**Skills:** Arcana +9, Athletics +9, Perception +6, Stealth +5

---

### Traits

**Legendary Resistance (3/Day).** If Muiral fails a saving throw, he can choose to succeed instead.


---

### Actions

**Multiattack.** Muiral makes three attacks: two with his longsword and one with his sting.

**Longsword.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage, or 15 (2d10 + 4) slashing damage if used with two hands.

**Sting.** Melee Weapon Attack: +9 to hit, reach 10 ft., one creature. *Hit:* 9 (1d10 + 4) piercing damage. The target must make a DC 16 Constitution saving throw, taking 27 (6d8) poison damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Cast Cantrip.** Muiral casts a cantrip.

**Lunging Attack (Costs 2 Actions).** Muiral makes one longsword attack that has a reach of 10 feet.

**Retreating Strike (Costs 3 Actions).** Muiral moves up to his speed without provoking opportunity attacks. Before the move, he can make one longsword attack.


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