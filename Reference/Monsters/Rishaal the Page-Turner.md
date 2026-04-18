---
type: pc
race: "Humanoid (dragonborn)"
class:
 - "Rishaal the Page-Turner"
subClass:
 - "CR 6"
cover: "Rishaal the Page-Turner.png"
campaign:
locations:
tags:
  - race/dragonborn
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/6
  - source/wdh
---
###### Rishaal the Page-Turner
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Rishaal the Page-Turner.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dragonborn) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 40 (9d8) |
> | :FasUserGroup: Race | Humanoid (dragonborn) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 11 | 17 | 12 | 11 |
| **Mod** | -1 | +2 | +0 | +3 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Draconic, Dwarvish, Elvish
**Saving Throws:** Int +6, Wis +4
**Skills:** Arcana +6, History +6
**Damage Resistances:** fire

---

### Actions

**Breath Weapon.** Rishaal can use his action to exhale a 15-foot cone of fire (but can't do this again until he finishes a short or long rest); each creature in the cone must make a DC 10 Dexterity saving throw, taking 2d6 fire damage on a failed save, or half as much damage on a successful one.

**Dagger.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage. Or Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


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