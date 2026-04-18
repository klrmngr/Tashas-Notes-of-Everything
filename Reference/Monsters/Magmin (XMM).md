---
type: pc
race: "Elemental"
class:
 - "Magmin"
subClass:
 - "CR 1/2"
cover: "Magmin.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/small
  - cr/1-2
  - source/xmm
---
###### Magmin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Magmin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Elemental |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 13 (3d6 + 3) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 15 | 12 | 8 | 11 | 10 |
| **Mod** | -2 | +2 | +1 | -1 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Primordial (Ignan)
**Damage Immunities:** fire

---

### Traits

**Death Burst.** The magmin explodes when it dies. dex DC 11, each creature in a 10-foot Emanation originating from the magmin.  7 (2d6) Fire damage.  Half damage.


---

### Actions

**Touch.** m +4, reach 5 ft. *Hit:* 7 (2d4 + 2) Fire damage. If the target is a creature or a flammable object that isn't being worn or carried, it starts burning.


---

### Bonus Actions

**Ignited Illumination.** The magmin sets itself ablaze or extinguishes its flames. While ablaze, the magmin sheds Bright Light in a 10-foot radius and Dim Light for an additional 10 feet.


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