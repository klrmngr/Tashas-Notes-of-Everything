---
type: pc
race: "Humanoid (human, sorcerer)"
class:
 - "Sion"
subClass:
 - "CR 2"
cover: "Sion.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/qftis
---
###### Sion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Sion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human, sorcerer) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 49 (9d8 + 9) |
> | :FasUserGroup: Race | Humanoid (human, sorcerer) |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 13 | 12 | 14 | 16 |
| **Mod** | +3 | +2 | +1 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** Common
**Saving Throws:** Con +3, Cha +5
**Skills:** Arcana +3, Perception +4, Stealth +6

---

### Traits

**Magic Resistance.** Sion has advantage on saving throws against spells and other magical effects if he is in dim light or darkness.

**Shadesight.** Magical darkness doesn't impede Sion's darkvision.

**Shadowy Demise.** If Sion dies, his body melts into shadow, leaving behind only equipment he was wearing or carrying.

**Sunlight Weakness.** While in sunlight, Sion has disadvantage on attack rolls, ability checks, and saving throws.


---

### Actions

**Multiattack.** Sion makes one Shadow Sword attack and uses Affix Shadow or Spellcasting.

**Shadow Sword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 14 (2d10 + 3) necrotic damage.

**Affix Shadow.** Sion targets a creature within 60 feet of himself that he can see. That target must make a DC 13 Charisma saving throw. On a failed save, the target has the grappled condition (escape DC 13) as its shadow wraps around it. Once the target escapes the grapple, its shadow returns to normal.


---

### Bonus Actions

**Shadow Step.** While Sion is in dim light or darkness, he magically teleports up to 15 feet to an unoccupied space he can see that is also in dim light or darkness.


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