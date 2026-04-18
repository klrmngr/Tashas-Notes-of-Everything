---
type: pc
race: "Aberration"
class:
 - "Mind Flayer"
subClass:
 - "CR 7"
cover: "Mind Flayer.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/7
  - source/xmm
---
###### Mind Flayer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Mind Flayer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 99 (18d8 + 18) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 12 | 12 | 19 | 17 | 17 |
| **Mod** | +0 | +1 | +1 | +4 | +3 | +3 |

**Speed:** 30 ft., fly 15 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 16
**Languages:** Deep Speech, Undercommon; telepathy 120 ft.
**Saving Throws:** Dex +4, Int +7, Wis +6, Cha +6
**Skills:** Arcana +7, Insight +6, Perception +6, Stealth +4
**Damage Resistances:** psychic

---

### Traits

**Magic Resistance.** The mind flayer has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Tentacles.** m +7, reach 5 ft. *Hit:* 22 (4d8 + 4) Psychic damage. If the target is a Medium or smaller creature, it has the Grappled condition (escape DC 14) from all the mind flayer's tentacles, and the target has the Stunned condition until the grapple ends.

**Extract Brain.** con DC 15, one creature that is Grappled by the mind flayer's Tentacles.  55 (10d10) Piercing damage.  Half damage.  If this damage reduces the target to 0 Hit Points, the mind flayer kills it and devours its brain.

**Mind Blast (Recharge 5–6).** int DC 15, each creature in a 60-foot Cone.  31 (6d8 + 4) Psychic damage, and the target has the Stunned condition until the end of the mind flayer's next turn.  Half damage only.


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