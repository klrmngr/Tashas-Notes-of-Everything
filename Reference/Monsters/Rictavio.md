---
type: pc
race: "Humanoid (human)"
class:
 - "Rictavio"
subClass:
 - "CR 5"
cover: "Rictavio.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/cos
---
###### Rictavio
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Curse of Strahd
___

> [!infobox|no-t right]
> ![[Rictavio.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 12 (leather armor) |
> | :FasHeart: HP | 77 (14d8 + 14) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Curse of Strahd |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 12 | 13 | 16 | 18 | 16 |
| **Mod** | -1 | +1 | +1 | +3 | +4 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Abyssal, Common, Elvish, Infernal
**Saving Throws:** Con +4, Wis +7
**Skills:** Arcana +9, Insight +7, Medicine +7, Perception +7, Religion +6, Sleight Of Hand +4

---

### Traits

**Special Equipment.** In addition to his sword cane, Rictavio wears a hat of disguise and a ring of mind shielding, and he carries a spell scroll of raise dead.

**Undead Slayer.** When Rictavio hits an undead with a weapon attack, the undead takes an extra 10 (3d6) damage of the weapon's type.


---

### Actions

**Multiattack.** Rictavio makes two attacks with his sword cane.

**Sword Cane.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) bludgeoning damage (wooden cane) or piercing damage (silvered sword).


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