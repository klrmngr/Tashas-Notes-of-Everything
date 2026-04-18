---
type: pc
race: "Humanoid (half-elf)"
class:
 - "Kalain"
subClass:
 - "CR 2"
cover: "Kalain.png"
campaign:
locations:
tags:
  - race/half-elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/wdh
---
###### Kalain
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Kalain.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (half-elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (chain shirt) |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Humanoid (half-elf) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 12 | 10 | 13 | 14 |
| **Mod** | +0 | +2 | +1 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Common, Elvish
**Saving Throws:** Dex +4, Wis +3
**Skills:** Acrobatics +4, Perception +5, Performance +6

---

### Traits

**Fey Ancestry.** Kalain has advantage on saving throws against being charmed and magic can't put her to sleep.

**Art Imitates Life (3/Day).** Kalain touches one of her paintings and causes its subject to spring forth, becoming a creature of that kind provided its CR is 3 or lower. The creature appears in an unoccupied space within 5 feet of the painting, which becomes blank. The creature is friendly toward Kalain and hostile toward all others. It rolls initiative to determine when it acts. It disappears after 1 minute, when it is reduced to 0 hit points, or when Kalain dies or falls unconscious.

**Taunt (2/Day).** Kalain can use a bonus action on her turn to target one creature within 30 feet of it. If the target can hear Kalain, the target must succeed on a DC 12 Charisma saving throw or have disadvantage on ability checks, attack rolls, and saving throws until the start of Kalain's next turn.


---

### Actions

**Shortsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.

**Shortbow.** Ranged Weapon Attack: +4 to hit, range 80/320 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.


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