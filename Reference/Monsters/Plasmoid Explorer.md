---
type: pc
race: "Ooze"
class:
 - "Plasmoid Explorer"
subClass:
 - "CR 1/4"
cover: "Plasmoid Explorer.png"
campaign:
locations:
tags:
  - race/ooze
  - affinity/hostile
  - type/ooze
  - size/medium
  - cr/1-4
  - source/bam
---
###### Plasmoid Explorer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Plasmoid Explorer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Ooze |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 16 (3d8 + 3) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 12 | 12 | 10 | 14 | 10 |
| **Mod** | +1 | +1 | +1 | +0 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common
**Skills:** Perception +4, Survival +4
**Damage Resistances:** acid; poison

---

### Traits

**Amorphous.** The plasmoid can squeeze through a space as narrow as 1 inch wide, provided it is wearing and carrying nothing. It has advantage on ability checks it makes to initiate or escape a grapple.

**Hold Breath.** The plasmoid can hold its breath for 1 hour.


---

### Actions

**Multiattack.** The plasmoid makes two Pseudopod attacks. It can replace one of those attacks with a Javelin attack.

**Pseudopod.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) bludgeoning damage.

**Javelin.** Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 4 (1d6 + 1) piercing damage.


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