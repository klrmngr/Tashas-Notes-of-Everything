---
type: pc
race: "Monstrosity"
class:
 - "Corrupted Avatar of Lurue"
subClass:
 - "CR 8"
cover: "Corrupted Avatar of Lurue.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/8
  - source/cm
---
###### Corrupted Avatar of Lurue
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Corrupted Avatar of Lurue.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 90 (12d10 + 24) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 15 | 11 | 17 | 16 |
| **Mod** | +4 | +2 | +2 | +0 | +3 | +3 |

**Speed:** 50 ft., fly 50 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Celestial, Elvish, Sylvan, telepathy 60 ft.
**Saving Throws:** Int +3, Wis +6, Cha +6
**Damage Immunities:** poison
**Condition Immunities:** charmed; paralyzed; poisoned

---

### Actions

**Multiattack.** The avatar makes two attacks: one with its hooves and one with its horn.

**Hooves.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 32 (8d6 + 4) necrotic damage.

**Horn.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 32 (8d6 + 4) necrotic damage. If the target is a humanoid, it must succeed on a DC 13 Wisdom saving throw or be transformed into a wolf under the avatar's control. This transformation lasts for 1 hour, or until the target drops to 0 hit points or dies. The target's game statistics are replaced by the wolf's statistics, but it retains its hit points. The target is limited in the actions it can perform by the nature of its wolf form, and it can't speak, cast spells, or take any other action that requires hands or speech. The target's gear melds into the new form, and it can't activate, use, wield, or otherwise benefit from any of its equipment.


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