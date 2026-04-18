---
type: pc
race: "Celestial (angel)"
class:
 - "Planetar"
subClass:
 - "CR 16"
cover: "Planetar.png"
campaign:
locations:
tags:
  - race/angel
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/16
  - source/xmm
---
###### Planetar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Planetar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Large Celestial (angel) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 262 (21d10 + 147) |
> | :FasUserGroup: Race | Celestial (angel) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 20 | 24 | 19 | 22 | 25 |
| **Mod** | +7 | +5 | +7 | +4 | +6 | +7 |

**Speed:** 40 ft., fly 120 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 21
**Languages:** all; telepathy 120 ft.
**Saving Throws:** Str +12, Con +12, Wis +11, Cha +12
**Skills:** Perception +11
**Damage Resistances:** radiant
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Divine Awareness.** The planetar knows if it hears a lie.

**Exalted Restoration.** If the planetar dies outside Mount Celestia, its body disappears, and it gains a new body instantly, reviving with all its Hit Points somewhere in Mount Celestia.

**Magic Resistance.** The planetar has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The planetar makes three Radiant Sword attacks or uses Holy Burst twice.

**Radiant Sword.** m +12, reach 10 ft. *Hit:* 14 (2d6 + 7) Slashing damage plus 18 (4d8) Radiant damage.

**Holy Burst.** dex DC 20, each enemy in a 20-foot-radius Sphere centered on a point the planetar can see within 120 feet.  24 (7d6) Radiant damage.  Half damage.


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