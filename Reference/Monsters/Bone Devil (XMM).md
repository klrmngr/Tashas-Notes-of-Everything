---
type: pc
race: "Fiend (devil)"
class:
 - "Bone Devil"
subClass:
 - "CR 9"
cover: "Bone Devil.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/9
  - source/xmm
---
###### Bone Devil
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Bone Devil.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 161 (17d10 + 68) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 16 | 18 | 13 | 14 | 16 |
| **Mod** | +4 | +3 | +4 | +1 | +2 | +3 |

**Speed:** 40 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft. (unimpeded by magical Darkness), passive Perception 12
**Languages:** Infernal; telepathy 120 ft.
**Saving Throws:** Str +8, Int +5, Wis +6, Cha +7
**Skills:** Deception +7, Insight +6
**Damage Resistances:** cold
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Diabolical Restoration.** If the devil dies outside the Nine Hells, its body disappears in sulfurous smoke, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Nine Hells.

**Magic Resistance.** The devil has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The devil makes two Claw attacks and one Infernal Sting attack.

**Claw.** m +8, reach 10 ft. *Hit:* 13 (2d8 + 4) Slashing damage.

**Infernal Sting.** m +8, reach 10 ft. *Hit:* 15 (2d10 + 4) Piercing damage plus 18 (4d8) Poison damage, and the target has the Poisoned condition until the start of the devil's next turn. While Poisoned, the target can't regain Hit Points.


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