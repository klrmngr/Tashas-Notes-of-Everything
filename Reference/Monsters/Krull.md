---
type: pc
race: "Humanoid (tortle)"
class:
 - "Krull"
subClass:
 - "CR 6"
cover: "Krull.png"
campaign:
locations:
tags:
  - race/tortle
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/6
  - source/bgdia
---
###### Krull
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Krull.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Humanoid (tortle) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 117 (18d8 + 36) |
> | :FasUserGroup: Race | Humanoid (tortle) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 15 | 12 | 20 | 12 |
| **Mod** | +5 | +2 | +2 | +1 | +5 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Aquan, Common, Draconic
**Saving Throws:** Wis +8, Cha +4
**Skills:** Arcana +4, Medicine +8, Nature +4, Survival +8

---

### Traits

**Hold Breath.** Krull can hold his breath for 1 hour.

**Inescapable Destruction.** Necrotic damage dealt by Krull's spells ignores resistance to necrotic damage.


---

### Actions

**Claws.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 7 (1d4 + 5) piercing damage.

**+1 Maul.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) bludgeoning damage plus 9 (2d8) necrotic damage.

**Shell Defense.** Krull withdraws into his shell. Until he emerges as a bonus action, he has a +4 bonus to AC and has advantage on Strength and Constitution saving throws. While in his shell, Krull is prone, his speed is 0 and can't increase, he has disadvantage on Dexterity saving throws, he can't take reactions, and the only action he can take is to emerge from his shell.


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