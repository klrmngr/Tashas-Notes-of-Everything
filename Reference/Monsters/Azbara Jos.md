---
type: pc
race: "Humanoid (human)"
class:
 - "Azbara Jos"
subClass:
 - "CR 4"
cover: "Azbara Jos.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/hotdq
---
###### Azbara Jos
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Hoard of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Azbara Jos.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13; 16 with mage armor |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Hoard of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 16 | 14 | 16 | 13 | 11 |
| **Mod** | -1 | +3 | +2 | +3 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Draconic, Infernal, Primordial, Thayan
**Saving Throws:** Int +5, Wis +3
**Skills:** Arcana +5, Deception +2, Insight +3, Stealth +5

---

### Traits

**Special Equipment.** Azbara has two scrolls of mage armor.

**Potent Cantrips.** When Azbara casts an evocation Cantrips and misses, or the target succeeds on its saving throw, the target still takes half the cantrip's damage but suffers no other effect.

**Sculpt Spells.** When Azbara casts an evocation spell that affects other creatures that he can see, he can choose a number of them equal to 1+the spell's level to succeed on their saving throws against the spell. Those creatures take no damage if they would normally take half damage from the spell.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or ranged 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.


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