---
type: pc
race: "Undead"
class:
 - "Grim Champion of Bloodshed"
subClass:
 - "CR 20"
cover: "Grim Champion of Bloodshed.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/20
  - source/bmt
---
###### Grim Champion of Bloodshed
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Grim Champion of Bloodshed.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 280 (33d8 + 132) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 12 | 18 | 10 | 17 | 21 |
| **Mod** | +6 | +1 | +4 | +0 | +3 | +5 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 19
**Languages:** Common
**Saving Throws:** Str +12, Dex +7, Con +10
**Skills:** Athletics +12, Intimidation +11, Perception +9
**Damage Resistances:** cold; necrotic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; poisoned; stunned; unconscious

---

### Traits

**Legendary Resistance (3/Day).** If the champion fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The champion makes four Blazing Morningstar attacks. It can replace one of these attacks with Blade Storm, if available.

**Blazing Morningstar.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 10 (1d8 + 6) piercing damage plus 14 (4d6) fire damage.

**Blade Storm (Recharge 5–6).** The champion conjures a churning storm of spectral blades that fills a 20-foot cube centered on a point it can see within 120 feet of itself. The storm lasts until the start of the champion's next turn. While the storm is active, the area of the storm is difficult terrain. Whenever a creature enters the storm for the first time on a turn or starts its turn there, it must make a DC 19 Dexterity saving throw, taking 27 (6d8) slashing damage on a failed saving throw, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Furious Pursuit.** The champion moves up to its speed or commands its mount to move up to its speed. This movement doesn't provoke opportunity attacks.

**Induce Violence.** The champion targets one creature it can see within 60 feet of itself. The target must succeed on a DC 19 Wisdom saving throw or immediately make one melee weapon attack against another creature of the champion's choice that is within the target's reach. If no creature is within the target's reach or if the target has the incapacitated condition, the target instead takes 11 (2d10) psychic damage.

**Menace (Costs 2 Actions).** The champion chooses any number of creatures it can see within 30 feet of itself. Each target must succeed on a DC 19 Wisdom saving throw or have the frightened condition until the end of its next turn.


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