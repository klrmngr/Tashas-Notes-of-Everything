---
type: pc
race: "Fiend (devil)"
class:
 - "Harvester Devil"
subClass:
 - "CR 3"
cover: "Harvester Devil.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/3
  - source/abh
---
###### Harvester Devil
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: ABH
___

> [!infobox|no-t right]
> ![[Harvester Devil.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | ABH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 17 | 14 | 14 | 13 | 19 |
| **Mod** | +1 | +3 | +2 | +2 | +1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft. (unimpeded by magical Darkness), passive Perception 13
**Languages:** Common, Infernal; telepathy 120 ft.
**Saving Throws:** Con +4, Wis +3
**Skills:** Perception +3, Persuasion +8, Stealth +5
**Damage Resistances:** cold
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Diabolic Ward.** Attack rolls against the devil have Disadvantage. If the devil makes an attack roll, this trait is suppressed until the start of its next turn.

**Diabolical Restoration.** If the devil dies outside the Nine Hells, its body disappears in sulfurous smoke, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Nine Hells.

**Magic Resistance.** The devil has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The devil makes two attacks, using Infernal Blade or Confounding Ray in any combination.

**Infernal Blade.** m +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Slashing damage and 7 (2d6) Fire damage.

**Confounding Ray.** r +5, range 120 ft. *Hit:* 13 (2d12) Psychic damage. If the target is a creature, it can't make Opportunity Attacks until the start of the devil's next turn.

**Compelling Contract (1/Day).** cha DC 14, one creature within 30 feet of the devil.  The target has the Charmed condition. While it is Charmed, it has the Stunned condition, except the target can speak. If the target agrees to the devil's contract, the effect ends. Otherwise, the target repeats the save whenever it takes damage and at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.


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