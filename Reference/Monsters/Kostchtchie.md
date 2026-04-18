---
type: pc
race: "Fiend (demon)"
class:
 - "Kostchtchie"
subClass:
 - "CR 25"
cover: "Kostchtchie.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/25
  - source/bgdia
---
###### Kostchtchie
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Kostchtchie.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 25 (75,000 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 243 (18d10 + 144) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 12 | 27 | 18 | 22 | 19 |
| **Mod** | +10 | +1 | +8 | +4 | +6 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 24
**Languages:** Abyssal, Giant, telepathy 120 ft.
**Saving Throws:** Dex +9, Con +16, Wis +14
**Skills:** Intimidation +12, Perception +14, Survival +14
**Damage Resistances:** fire; lightning
**Damage Immunities:** cold; poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Kostchtchie fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Kostchtchie has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Kostchtchie makes two melee attacks, only one of which can be a bite attack.

**Bite.** Melee Weapon Attack: +18 to hit, reach 5 ft., one creature. *Hit:* 13 (1d6 + 10) piercing damage.

**Matalotok (Warhammer).** Melee Weapon Attack: +18 to hit, reach 10 ft., one target. *Hit:* 19 (2d8 + 10) bludgeoning damage, or 21 (2d10 + 10) bludgeoning damage when used with two hands, and the weapon emits a burst of cold that deals 10 (3d6) cold damage to each creature within 30 feet of it.


---

### Legendary Actions

### 

**Attack.** Kostchtchie makes one melee weapon attack.

**Charge.** Kostchtchie moves up to his speed.

**Curse (Costs 2 Actions).** Kostchtchie curses one creature he can see within 60 feet of him. The cursed creature gains vulnerability to all damage dealt by Kostchtchie until the end of Kostchtchie's next turn.


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