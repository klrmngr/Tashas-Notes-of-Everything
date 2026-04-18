---
type: pc
race: "Elemental"
class:
 - "Water Elemental Myrmidon"
subClass:
 - "CR 7"
cover: "Water Elemental Myrmidon.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/7
  - source/mpmm
---
###### Water Elemental Myrmidon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Water Elemental Myrmidon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 127 (17d8 + 51) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 16 | 8 | 10 | 10 |
| **Mod** | +4 | +2 | +3 | -1 | +0 | +0 |

**Speed:** 40 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Aquan, one language of its creator's choice
**Damage Resistances:** acid; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** paralyzed; petrified; poisoned; prone

---

### Actions

**Multiattack.** The myrmidon makes three Trident attacks.

**Trident.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 7 (1d6 + 4) force damage, or 8 (1d8 + 4) force damage if used with two hands to make a melee attack.

**Freezing Strikes (Recharge 6).** The myrmidon uses Multiattack. Each attack that hits deals an extra 5 (1d10) cold damage. A target that is hit by one or more of these attacks has its speed reduced by 10 feet until the end of the myrmidon's next turn.


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