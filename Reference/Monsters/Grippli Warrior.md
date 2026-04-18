---
type: pc
race: "Humanoid (grippli)"
class:
 - "Grippli Warrior"
subClass:
 - "CR 1/4"
cover: "Grippli Warrior.png"
campaign:
locations:
tags:
  - race/grippli
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-4
  - source/cm
---
###### Grippli Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Grippli Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Humanoid (grippli) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 13 (3d6 + 3) |
> | :FasUserGroup: Race | Humanoid (grippli) |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 12 | 10 | 14 | 10 |
| **Mod** | +0 | +2 | +1 | +0 | +2 | +0 |

**Speed:** 30 ft., climb 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Grippli plus one other language (usually Common, Draconic, or Primordial)
**Skills:** Athletics +2, Stealth +4, Survival +4

---

### Traits

**Hold Breath.** The grippli can hold its breath for 20 minutes.

**Standing Leap.** The grippli can leap 30 feet horizontally or 20 feet vertically from a standing position.


---

### Actions

**Multiattack.** The grippli makes one attack with its tongue. If this attack hits, the grippli can make a melee attack using its trident against the same target.

**Tongue.** Melee Weapon Attack: +4 to hit, reach 5 ft., one Medium or smaller creature. *Hit:* The target is grappled (escape DC 12). Until this grapple ends, the target is restrained, and the grippli can't grab another creature.

**Trident.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing damage if used with two hands to make a melee attack, plus 2 (1d4) piercing damage if the grippli had advantage on the attack roll.

**Shortbow.** Ranged Weapon Attack: +4 to hit, range 80/320 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, plus 2 (1d4) piercing damage if the grippli had advantage on the attack roll.


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