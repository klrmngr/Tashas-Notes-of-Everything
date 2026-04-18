---
type: pc
race: "Humanoid (firenewt)"
class:
 - "Firenewt Warlock of Imix"
subClass:
 - "CR 1"
cover: "Firenewt Warlock of Imix.png"
campaign:
locations:
tags:
  - race/firenewt
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/vgm
---
###### Firenewt Warlock of Imix
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Firenewt Warlock of Imix.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (firenewt) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 10; 13 with mage armor |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid (firenewt) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 11 | 12 | 9 | 11 | 14 |
| **Mod** | +1 | +0 | +1 | -1 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft. (penetrates magical darkness), passive Perception 10
**Languages:** Draconic, Ignan
**Damage Immunities:** fire

---

### Traits

**Amphibious.** The firenewt can breathe air and water.

**Imix's Blessing.** When the firenewt reduces an enemy to 0 hit points, the firenewt gains 5 temporary hit points.


---

### Actions

**Morningstar.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 5 (1d8 + 1) piercing damage.


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