---
type: pc
race: "Ooze"
class:
 - "Plasmoid Warrior"
subClass:
 - "CR 3"
cover: "Plasmoid Warrior.png"
campaign:
locations:
tags:
  - race/ooze
  - affinity/hostile
  - type/ooze
  - size/medium
  - cr/3
  - source/bam
---
###### Plasmoid Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Plasmoid Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Ooze |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (natural armor, shield) |
> | :FasHeart: HP | 71 (11d8 + 22) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 14 | 10 | 11 | 10 |
| **Mod** | +3 | +2 | +2 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common
**Skills:** Athletics +5, Stealth +4
**Damage Resistances:** acid; poison

---

### Traits

**Amorphous.** The plasmoid can squeeze through a space as narrow as 1 inch wide, provided it is wearing and carrying nothing. It has advantage on ability checks it makes to initiate or escape a grapple.

**Hold Breath.** The plasmoid can hold its breath for 1 hour.


---

### Actions

**Multiattack.** The plasmoid makes three Pseudopod attacks. It can replace one of those attacks with a Spear or Pistol attack.

**Pseudopod.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) bludgeoning damage.

**Spear.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage, or 7 (1d8 + 3) piercing damage when used with two hands to make a melee attack.

**Pistol.** Ranged Weapon Attack: +4 to hit, range 30/90 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage.


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