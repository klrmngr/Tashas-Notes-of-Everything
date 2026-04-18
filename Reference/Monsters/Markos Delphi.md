---
type: pc
race: "Humanoid (human, warlock)"
class:
 - "Markos Delphi"
subClass:
 - "CR 3"
cover: "Markos Delphi.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/kftgv
---
###### Markos Delphi
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Keys from the Golden Vault
___

> [!infobox|no-t right]
> ![[Markos Delphi.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human, warlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Humanoid (human, warlock) |
> | :FasBook: Source | Keys from the Golden Vault |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 15 | 12 | 17 | 13 | 16 |
| **Mod** | -1 | +2 | +1 | +3 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Celestial, Common, Deep Speech
**Saving Throws:** Wis +3, Cha +5
**Skills:** Arcana +7, History +7, Perception +3
**Damage Immunities:** psychic

---

### Actions

**Multiattack.** Markos makes two Ceremonial Blade attacks, two Psychic Orb attacks, or one of each.

**Ceremonial Blade.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage plus 3 (1d6) poison damage. If the target is a creature, it must succeed on a DC 13 Constitution saving throw or become poisoned for 1 minute. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Psychic Orb.** Ranged Spell Attack: +5 to hit, range 60 ft., one creature. *Hit:* 10 (2d6 + 3) psychic damage.


---

### Bonus Actions

**Swap Space.** Markos targets one Medium or Small creature he can see within 30 feet of himself. The target must succeed on a DC 13 Constitution saving throw or it teleports, along with any equipment it is wearing or carrying, exchanging positions with Markos.


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