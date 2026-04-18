---
type: pc
race: "Fiend (devil)"
class:
 - "Chain Devil"
subClass:
 - "CR 8"
cover: "Chain Devil.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/8
  - source/xmm
---
###### Chain Devil
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Chain Devil.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 85 (10d8 + 40) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 18 | 11 | 12 | 14 |
| **Mod** | +4 | +2 | +4 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft. (unimpeded by magical Darkness), passive Perception 11
**Languages:** Infernal; telepathy 120 ft.
**Saving Throws:** Con +7, Wis +4
**Damage Resistances:** bludgeoning; cold; piercing; slashing
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Diabolical Restoration.** If the devil dies outside the Nine Hells, its body disappears in sulfurous smoke, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Nine Hells.

**Magic Resistance.** The devil has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The devil makes two Chain attacks and uses Conjure Infernal Chain.

**Chain.** m +7, reach 10 ft. *Hit:* 11 (2d6 + 4) Slashing damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 14) from one of two chains, and it has the Restrained condition until the grapple ends.

**Conjure Infernal Chain.** The devil conjures a fiery chain to bind a creature. dex DC 15, one creature the devil can see within 60 feet.  9 (2d4 + 4) Fire damage, and the target has the Restrained condition until the end of the devil's next turn, at which point the chain disappears. If the target is Large or smaller, the devil moves the target up to 30 feet straight toward itself.  The chain disappears.


---

### Reactions

**Unnerving Gaze.**  A creature the devil can see starts its turn within 30 feet of the devil and can see the devil. dwis DC 15, the triggering creature.  The target has the Frightened condition until the end of its turn.  The target is immune to this devil's Unnerving Gaze for 24 hours.


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