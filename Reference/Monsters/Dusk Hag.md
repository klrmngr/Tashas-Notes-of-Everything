---
type: pc
race: "Fey"
class:
 - "Dusk Hag"
subClass:
 - "CR 6"
cover: "Dusk Hag.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/6
  - source/erlw
---
###### Dusk Hag
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Dusk Hag.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 82 (15d8 + 15) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 12 | 17 | 16 | 18 |
| **Mod** | +0 | +2 | +1 | +3 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 16
**Languages:** Common, Giant, Infernal
**Saving Throws:** Int +6, Wis +6
**Skills:** Deception +7, Insight +6, Perception +6
**Condition Immunities:** blinded; charmed; frightened

---

### Traits

**Magic Resistance.** The hag has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The hag makes two Nightmare Touch attacks.

**Claws.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) slashing damage.

**Nightmare Touch.** Melee Spell Attack: +7 to hit, reach 5 ft., one creature. *Hit:* 18 (4d6 + 4) psychic damage. If the target is unconscious, it takes an extra 10 (3d6) psychic damage and is cursed until the hag dies or the curse is removed. The cursed creature's hit point maximum decreases by 5 (1d10) whenever it finishes a long rest.


---

### Reactions

**Dream Eater.** When an unconscious creature the hag can see within 30 feet of her regains consciousness, the hag can force the creature to make a DC 15 Wisdom saving throw. Unless the save succeeds, the creature takes 11 (2d10) psychic damage, and the hag regains hit points equal to the amount of damage taken.


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