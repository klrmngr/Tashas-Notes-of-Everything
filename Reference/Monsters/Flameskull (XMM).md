---
type: pc
race: "Undead"
class:
 - "Flameskull"
subClass:
 - "CR 4"
cover: "Flameskull.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/tiny
  - cr/4
  - source/xmm
---
###### Flameskull
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Flameskull.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Tiny Undead |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 40 (9d4 + 18) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 17 | 14 | 16 | 10 | 11 |
| **Mod** | -5 | +3 | +2 | +3 | +0 | +0 |

**Speed:** 5 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** Common plus two other languages
**Skills:** Arcana +5, Perception +2
**Damage Immunities:** fire; necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned; prone

---

### Traits

**Illumination.** The flameskull sheds Bright Light in a 15-foot radius and Dim Light for an additional 15 feet.

**Magic Resistance.** The flameskull has Advantage on saving throws against spells and other magical effects.

**Undead Restoration.** If the flameskull is destroyed, it regains all its Hit Points in 1 hour unless Holy Water is sprinkled on its remains or the Dispel Evil and Good spell is cast on them.


---

### Actions

**Multiattack.** The flameskull makes two Fire Ray attacks.

**Fire Ray.** m,r +5, reach 5 ft. or range 60 ft. *Hit:* 13 (3d6 + 3) Fire damage.


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