---
type: pc
race: "Fiend (devil)"
class:
 - "Horned Devil"
subClass:
 - "CR 11"
cover: "Horned Devil.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/11
  - source/xmm
---
###### Horned Devil
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Horned Devil.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 199 (19d10 + 95) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 17 | 21 | 12 | 16 | 18 |
| **Mod** | +6 | +3 | +5 | +1 | +3 | +4 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Darkvision 150 ft. (unimpeded by magical Darkness), passive Perception 13
**Languages:** Infernal; telepathy 120 ft.
**Saving Throws:** Str +10, Dex +7, Wis +7, Cha +8
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Diabolical Restoration.** If the devil dies outside the Nine Hells, its body disappears in sulfurous smoke, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Nine Hells.

**Magic Resistance.** The devil has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The devil makes three attacks, using Searing Fork or Hurl Flame in any combination. It can replace one attack with a use of Infernal Tail.

**Searing Fork.** m +10, reach 10 ft. *Hit:* 15 (2d8 + 6) Piercing damage plus 9 (2d8) Fire damage.

**Hurl Flame.** r +8, range 150 ft. *Hit:* 26 (5d8 + 4) Fire damage. If the target is a flammable object that isn't being worn or carried, it starts burning.

**Infernal Tail.** dex DC 17, one creature the devil can see within 10 feet.  10 (1d8 + 6) Necrotic damage, and the target receives an infernal wound if it doesn't have one. While wounded, the target loses 10 (3d6) Hit Points at the start of each of its turns. The wound closes after 1 minute, after a spell restores Hit Points to the target, or after the target or a creature within 5 feet of it takes an action to stanch the wound, doing so by succeeding on a DC 17 Wisdom (Medicine) check.


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