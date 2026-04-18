---
type: pc
race: "Monstrosity"
class:
 - "Strigoi"
subClass:
 - "CR 4"
cover: "Strigoi.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/4
  - source/vrgr
---
###### Strigoi
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Strigoi.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 52 (7d8 + 21) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 14 | 16 | 11 | 17 | 10 |
| **Mod** | +3 | +2 | +3 | +0 | +3 | +0 |

**Speed:** 30 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Common
**Saving Throws:** Str +5, Dex +4, Wis +5
**Skills:** Perception +5, Stealth +6
**Damage Resistances:** necrotic
**Condition Immunities:** charmed; frightened

---

### Traits

**Stirge Telepathy.** The strigoi can magically command any [[Stirge]] within 120 feet of it, using a limited form of telepathy.


---

### Actions

**Multiattack.** The strigoi makes one Claw attack and makes one Proboscis attack.

**Claw.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage plus 6 (1d12) acid damage.

**Proboscis.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 8 (1d10 + 3) piercing damage plus 10 (3d6) necrotic damage, and the strigoi regains hit points equal to the amount of necrotic damage dealt. A creature reduced to 0 hit points from this attack dies and leaves nothing behind except its skin and its equipment.

**Ravenous Children (1/Day).** The strigoi magically summons 1d4 + 2 stirges (see their entry in the Monster Manual) in unoccupied spaces it can see within 30 feet of it. The stirges are under the strigoi's control and act immediately after the strigoi in the initiative order. The stirges disappear after 1 hour, when the strigoi dies, or when the strigoi dismisses them (no action required).


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