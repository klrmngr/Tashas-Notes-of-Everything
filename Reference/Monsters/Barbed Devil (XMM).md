---
type: pc
race: "Fiend (devil)"
class:
 - "Barbed Devil"
subClass:
 - "CR 5"
cover: "Barbed Devil.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/5
  - source/xmm
---
###### Barbed Devil
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Barbed Devil.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 110 (13d8 + 52) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 17 | 18 | 12 | 14 | 14 |
| **Mod** | +3 | +3 | +4 | +1 | +2 | +2 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft. (unimpeded by magical Darkness), passive Perception 18
**Languages:** Infernal; telepathy 120 ft.
**Saving Throws:** Str +6, Con +7, Wis +5, Cha +5
**Skills:** Deception +5, Insight +5, Perception +8
**Damage Resistances:** cold
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Barbed Hide.** At the start of each of its turns, the devil deals 5 (1d10) Piercing damage to any creature it is grappling or any creature grappling it.

**Diabolical Restoration.** If the devil dies outside the Nine Hells, its body disappears in sulfurous smoke, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Nine Hells.

**Magic Resistance.** The devil has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The devil makes one Claws attack and one Tail attack, or it makes two Hurl Flame attacks.

**Claws.** m +6, reach 5 ft. *Hit:* 10 (2d6 + 3) Piercing damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 13) from both claws.

**Tail.** m +6, reach 10 ft. *Hit:* 14 (2d10 + 3) Slashing damage.

**Hurl Flame.** r +5, range 150 ft. *Hit:* 17 (5d6) Fire damage. If the target is a flammable object that isn't being worn or carried, it starts burning.


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