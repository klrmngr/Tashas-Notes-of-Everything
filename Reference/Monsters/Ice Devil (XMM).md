---
type: pc
race: "Fiend (devil)"
class:
 - "Ice Devil"
subClass:
 - "CR 14"
cover: "Ice Devil.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/14
  - source/xmm
---
###### Ice Devil
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ice Devil.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 228 (24d10 + 96) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 14 | 18 | 18 | 15 | 18 |
| **Mod** | +5 | +2 | +4 | +4 | +2 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 120 ft., passive Perception 17
**Languages:** Infernal; telepathy 120 ft.
**Saving Throws:** Dex +7, Con +9, Wis +7, Cha +9
**Skills:** Insight +7, Perception +7, Persuasion +9
**Damage Immunities:** cold; fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Diabolical Restoration.** If the devil dies outside the Nine Hells, its body disappears in sulfurous smoke, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Nine Hells.

**Magic Resistance.** The devil has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The devil makes three Ice Spear attacks. It can replace one attack with a Tail attack.

**Ice Spear.** m,r +10, reach 5 ft. or range 30/120 ft. *Hit:* 14 (2d8 + 5) Piercing damage plus 10 (3d6) Cold damage. Until the end of its next turn, the target can't take a Bonus Action or Reaction, its Speed decreases by 10 feet, and it can move or take one action on its turn, not both. The spear magically returns to the devil's hand immediately after a ranged attack.

**Tail.** m +10, reach 10 ft. *Hit:* 15 (3d6 + 5) Bludgeoning damage plus 18 (4d8) Cold damage.


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