---
type: pc
race: "Construct"
class:
 - "Brazen Gorgon"
subClass:
 - "CR 9"
cover: "Brazen Gorgon.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/9
  - source/xmm
---
###### Brazen Gorgon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Brazen Gorgon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 161 (17d10 + 68) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 19 | 2 | 14 | 7 |
| **Mod** | +4 | +2 | +4 | -4 | +2 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 20
**Languages:** —
**Skills:** Perception +10
**Damage Immunities:** fire
**Condition Immunities:** exhaustion; petrified

---

### Traits

**Flame Aura.** At the end of each of the gorgon's turns, each creature in a 5-foot Emanation originating from the gorgon takes 13 (3d8) Fire damage.

**Illumination.** The gorgon sheds Bright Light in a 10-foot radius and Dim Light for an additional 10 feet.


---

### Actions

**Multiattack.** The gorgon makes two Gore attacks.

**Gore.** m +8, reach 5 ft. *Hit:* 11 (2d6 + 4) Piercing damage plus 10 (3d6) Fire damage.

**Smelting Charge (Recharge 5–6).** The gorgon moves up to its Speed without provoking Opportunity Attacks and can move through the spaces of Medium or smaller creatures. Each time the gorgon enters a creature's space for the first time during this move, that target is subjected to the following effect. dex DC 16.  13 (2d8 + 4) Piercing damage plus 13 (3d8) Fire damage, and the target is pulled into the gorgon's space and has the Grappled condition (escape DC 14); if the gorgon already has a creature Grappled, the target has the Prone condition instead. Until the grapple ends, the target has the Restrained condition. When the gorgon moves, the Grappled target moves with it, costing no extra movement.


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