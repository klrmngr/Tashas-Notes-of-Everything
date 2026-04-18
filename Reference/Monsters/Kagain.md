---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Kagain"
subClass:
 - "CR 11"
cover: "Kagain.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/11
  - source/mabjov
---
###### Kagain
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Kagain.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 161 (17d8 + 85) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 20 | 10 | 11 | 10 |
| **Mod** | +4 | +1 | +5 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., passive Perception 14
**Languages:** Common, Dwarvish
**Saving Throws:** Str +8, Con +9
**Skills:** Athletics +8, Perception +4, Survival +4

---

### Traits

**Special Equipment.** Kagain wields a +3 greataxe. While Kagain is attuned to this weapon, his hit point maximum increases to 178. Whenever a hostile creature damages Kagain while the axe is in his possession, he must succeed on a DC 15 Wisdom saving throw or go berserk. He can choose to fail this saving throw. While berserk, Kagain gains advantage on all melee attacks and attacks made against him are made with advantage.


---

### Actions

**Multiattack.** Kagain makes three attacks with his Berserking Greataxe.

**Berserking Greataxe.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 13 (1d12 + 7) slashing damage.

**Heavy Crossbow.** Ranged Weapon Attack: +5 to hit, range 100/400 ft., one target. *Hit:* 6 (1d10 + 1) piercing damage.


---

### Legendary Actions

### 

**Weapon Attack.** Kagain makes a Berserking Greataxe attack.

**Berserk Whirlwind (Costs 3 Actions).** Kagain makes a Berserking Greataxe attack against every creature within 5 feet of him.


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