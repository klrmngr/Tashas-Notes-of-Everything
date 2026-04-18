---
type: pc
race: "Humanoid (bard, tiefling)"
class:
 - "Sythian Skalderang"
subClass:
 - "CR 7"
cover: "Sythian Skalderang.png"
campaign:
locations:
tags:
  - race/bard
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/kftgv
---
###### Sythian Skalderang
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Keys from the Golden Vault
___

> [!infobox|no-t right]
> ![[Sythian Skalderang.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (bard, tiefling) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (Graz'zt's gift) |
> | :FasHeart: HP | 99 (18d8 + 18) |
> | :FasUserGroup: Race | Humanoid (bard, tiefling) |
> | :FasBook: Source | Keys from the Golden Vault |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 13 | 14 | 11 | 16 |
| **Mod** | +0 | +2 | +1 | +2 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Abyssal, Common
**Saving Throws:** Dex +5, Wis +3
**Skills:** Arcana +5, Deception +6, Performance +6
**Damage Resistances:** fire

---

### Traits

**Fear of Frogs and Toads.** Sythian is frightened while he is within 20 feet of a frog or a toad (of any size) that he can see.

**Graz'zt's Gift.** Sythian's AC includes his Charisma modifier.


---

### Actions

**Multiattack.** Sythian makes two Poisoned Shortsword or Poisoned Dart attacks and uses Whispers of Azzagrat.

**Poisoned Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage plus 5 (1d10) poison damage.

**Poisoned Dart.** Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage plus 5 (1d10) poison damage.

**Whispers of Azzagrat.** Each creature in a 15-foot cube originating from Sythian must make a DC 14 Wisdom saving throw. On a failed save, a creature takes 18 (4d8) psychic damage and is incapacitated until the end of its next turn. On a successful save, the creature takes half as much damage and isn't incapacitated.


---

### Reactions

**Fiendish Rebuke (3/Day).** Immediately after a creature within 5 feet of Sythian hits him with an attack roll, Sythian forces that creature to make a DC 14 Constitution saving throw. The creature takes 14 (4d6) fire damage on a failed saving throw, or half as much damage on a successful one.


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