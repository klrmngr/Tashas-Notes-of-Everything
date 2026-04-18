---
type: pc
race: "Fiend (demon)"
class:
 - "Hezrou"
subClass:
 - "CR 8"
cover: "Hezrou.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/8
  - source/xmm
---
###### Hezrou
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Hezrou.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 157 (15d10 + 75) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 17 | 20 | 5 | 12 | 13 |
| **Mod** | +4 | +3 | +5 | -3 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 11
**Languages:** Abyssal; telepathy 120 ft.
**Saving Throws:** Str +7, Con +8, Wis +4
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Demonic Restoration.** If the hezrou dies outside the Abyss, its body dissolves into ichor, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Abyss.

**Magic Resistance.** The hezrou has Advantage on saving throws against spells and other magical effects.

**Stench.** con DC 16, any creature that starts its turn in a 10-foot Emanation originating from the hezrou.  The target has the Poisoned condition until the start of its next turn.


---

### Actions

**Multiattack.** The hezrou makes three Rend attacks.

**Rend.** m +7, reach 5 ft. *Hit:* 6 (1d4 + 4) Slashing damage plus 9 (2d8) Poison damage.


---

### Bonus Actions

**Leap.** The hezrou jumps up to 30 feet by spending 10 feet of movement.


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