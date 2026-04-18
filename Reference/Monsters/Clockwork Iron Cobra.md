---
type: pc
race: "Construct"
class:
 - "Clockwork Iron Cobra"
subClass:
 - "CR 4"
cover: "Clockwork Iron Cobra.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/4
  - source/mpmm
---
###### Clockwork Iron Cobra
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Clockwork Iron Cobra.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 91 (14d8 + 28) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 14 | 3 | 10 | 1 |
| **Mod** | +1 | +3 | +2 | -4 | +0 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands one language of its creator but can't speak
**Skills:** Stealth +7
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Magic Resistance.** The clockwork has advantage on saving throws against spells and other magical effects.

**Unusual Nature.** The clockwork doesn't require air, food, drink, or sleep.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage. If the target is a creature, it must succeed on a DC 13 Constitution saving throw or suffer one random effect (roll a d6):
- **1–2: Confusion.** On its next turn, the target must use its action to make one weapon attack against a random creature it can see within 30 feet of it, using whatever weapon it has in hand and moving beforehand if necessary to get in range. If it's holding no weapon, it makes an unarmed strike. If no creature is visible within 30 feet, it takes the Dash action, moving toward the nearest creature.
- **3–4: Paralysis.** The target is paralyzed until the end of its next turn.
- **5–6: Poison.** The target takes 13 (3d8) poison damage.


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