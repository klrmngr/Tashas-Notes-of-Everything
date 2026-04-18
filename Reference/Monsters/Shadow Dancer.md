---
type: pc
race: "Humanoid (elf)"
class:
 - "Shadow Dancer"
subClass:
 - "CR 7"
cover: "Shadow Dancer.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/mtf
---
###### Shadow Dancer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Shadow Dancer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 71 (13d8 + 13) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 13 | 11 | 12 | 12 |
| **Mod** | +1 | +3 | +1 | +0 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Elvish
**Saving Throws:** Dex +6, Cha +4
**Skills:** Stealth +6
**Damage Resistances:** necrotic
**Condition Immunities:** charmed; exhaustion

---

### Traits

**Fey Ancestry.** The shadow dancer has advantage on saving throws against being charmed, and magic can't put it to sleep.

**Shadow Jump.** As a bonus action, the shadow dancer can teleport up to 30 feet to an unoccupied space it can see. Both the space it teleports from and the space it teleports to must be in dim light or darkness. The shadow dancer can use this ability between the weapon attacks of another action it takes.


---

### Actions

**Multiattack.** The shadow dancer makes three spiked chain attacks.

**Spiked Chain.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 10 (2d6 + 3) piercing damage, and the target must succeed on a DC 14 Dexterity saving throw or suffer one additional effect of the shadow dancer's choice:
- The target is grappled (escape DC 14) if it is a Medium or smaller creature. Until the grapple ends, the target is restrained, and the shadow dancer can't grapple another target.
- The target is knocked prone.
- The target takes 22 (4d10) necrotic damage.


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