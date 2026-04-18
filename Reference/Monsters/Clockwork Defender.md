---
type: pc
race: "Construct"
class:
 - "Clockwork Defender"
subClass:
 - "CR 1"
cover: "Clockwork Defender.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1
  - source/kftgv
---
###### Clockwork Defender
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Keys from the Golden Vault
___

> [!infobox|no-t right]
> ![[Clockwork Defender.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 42 (5d8 + 20) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Keys from the Golden Vault |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 15 | 18 | 3 | 14 | 1 |
| **Mod** | +3 | +2 | +4 | -4 | +2 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** understands the languages of its creator but can't speak
**Skills:** Perception +6, Stealth +4
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Unusual Nature.** The defender doesn't need air, food, drink, or sleep.


---

### Actions

**Electrified Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage plus 7 (2d6) lightning damage. If the target is a creature, it must succeed on a DC 13 Strength saving throw or be grappled (escape DC 13). A creature grappled by the defender takes the damage again at the start of each of the defender's turns. The defender can have only one creature grappled in this way at a time, and the defender can't make Electrified Bite attacks while grappling.


---

### Bonus Actions

**Light Beam.** The defender emits bright light from its eyes in a 60-foot cone, or it shuts off this light.


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