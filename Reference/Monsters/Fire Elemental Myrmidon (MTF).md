---
type: pc
race: "Elemental"
class:
 - "Fire Elemental Myrmidon"
subClass:
 - "CR 7"
cover: "Fire Elemental Myrmidon.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/7
  - source/mtf
---
###### Fire Elemental Myrmidon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Fire Elemental Myrmidon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 123 (19d8 + 38) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 18 | 15 | 9 | 10 | 10 |
| **Mod** | +1 | +4 | +2 | -1 | +0 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Ignan, one language of its creator's choice
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** fire; poison
**Condition Immunities:** paralyzed; petrified; poisoned; prone

---

### Traits

**Illumination.** The myrmidon sheds bright light in a 20-foot radius and dim light in a 40-foot radius.

**Magic Weapons.** The myrmidon's weapon attacks are magical.

**Water Susceptibility.** For every 5 feet the myrmidon moves in 1 foot or more of water, it takes 2 (1d4) cold damage.


---

### Actions

**Multiattack.** The myrmidon makes three scimitar attacks.

**Scimitar.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage.

**Fiery Strikes (Recharge 6).** The myrmidon uses Multiattack. Each attack that hits deals an extra 5 (1d10) fire damage.


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