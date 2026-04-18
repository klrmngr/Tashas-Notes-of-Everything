---
type: pc
race: "Aberration"
class:
 - "Mind Flayer Arcanist"
subClass:
 - "CR 11"
cover: "Mind Flayer Arcanist.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/11
  - source/xmm
---
###### Mind Flayer Arcanist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Mind Flayer Arcanist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 143 (26d8 + 26) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 13 | 20 | 17 | 17 |
| **Mod** | +0 | +2 | +1 | +5 | +3 | +3 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 17
**Languages:** Deep Speech, Undercommon; telepathy 120 ft.
**Saving Throws:** Dex +6, Int +9, Wis +7, Cha +7
**Skills:** Arcana +13, Insight +7, Perception +7, Stealth +6
**Damage Immunities:** psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Magic Resistance.** The mind flayer has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The mind flayer makes three Arcane Tentacles attacks.

**Arcane Tentacles.** m,r +9, reach 5 ft. or range 120 ft. *Hit:* 27 (4d10 + 5) Psychic damage, and the mind flayer can teleport the target up to 30 feet to an unoccupied space the mind flayer can see on a surface or liquid large enough to support the target. If this damage reduces the target to 0 Hit Points, the mind flayer kills it and magically devours its brain.

**Mind Burst (Recharge 5–6).** int DC 17, each creature in a 40-foot Emanation originating from the mind flayer.  41 (8d8 + 5) Psychic damage, and the target has the Stunned condition until the end of the mind flayer's next turn.  Half damage only.


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