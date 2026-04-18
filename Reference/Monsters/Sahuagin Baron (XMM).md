---
type: pc
race: "Fiend"
class:
 - "Sahuagin Baron"
subClass:
 - "CR 5"
cover: "Sahuagin Baron.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/5
  - source/xmm
---
###### Sahuagin Baron
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Sahuagin Baron.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 76 (9d10 + 27) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 15 | 16 | 14 | 13 | 17 |
| **Mod** | +4 | +2 | +3 | +2 | +1 | +3 |

**Speed:** 30 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 17
**Languages:** Sahuagin
**Saving Throws:** Dex +5, Con +6, Wis +4
**Skills:** Perception +7
**Damage Resistances:** acid; cold

---

### Traits

**Blood Frenzy.** The sahuagin has Advantage on attack rolls against any creature that doesn't have all its Hit Points.

**Limited Amphibiousness.** The sahuagin can breathe air and water, but it must be submerged at least once every 4 hours to avoid suffocating outside water.

**Shark Telepathy.** The sahuagin can magically control sharks within 120 feet of itself, using a special telepathy.


---

### Actions

**Multiattack.** The sahuagin makes three Trident attacks.

**Trident.** m,r +7, reach 5 ft. or range 20/60 ft. *Hit:* 13 (2d8 + 4) Piercing damage.


---

### Reactions

**Fiendish Blood.**  The sahuagin takes Piercing or Slashing damage. dcon DC 14, each creature of the sahuagin's choice in a 5-foot Emanation originating from the sahuagin.  10 (3d6) Acid damage, and the target is cursed until it finishes a Short or Long Rest. While cursed, the target can't benefit from the Invisible condition, its Speed decreases by 10 feet, and all Fiends within 120 feet of the target can sense its location regardless of interposing obstacles.


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