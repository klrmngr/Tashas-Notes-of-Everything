---
type: pc
race: "Fiend (demon)"
class:
 - "Vlazok"
subClass:
 - "CR 11"
cover: "Vlazok.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/11
  - source/veor
---
###### Vlazok
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Vlazok.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 136 (16d10 + 48) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 18 | 16 | 6 | 9 | 9 |
| **Mod** | +5 | +4 | +3 | -2 | -1 | -1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** Abyssal, telepathy 120 ft.
**Saving Throws:** Str +9, Con +7
**Skills:** Perception +3
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**All-Around Vision.** The vlazok can't be surprised.

**Blood Frenzy.** The vlazok has advantage on melee attack rolls against any creature that doesn't have all its hit points.

**Magic Resistance.** The vlazok has advantage on saving throws against spells and other magical effects.

**Spider Climb.** The vlazok can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The vlazok makes two Gore attacks.

**Gore.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 23 (4d8 + 5) piercing damage, and if the target is a Large or smaller creature, it has the prone condition.


---

### Bonus Actions

**Stomp.** Melee Weapon Attack: +9 to hit, reach 5 ft., one prone creature. *Hit:* 27 (4d10 + 5) bludgeoning damage.


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