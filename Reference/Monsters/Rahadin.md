---
type: pc
race: "Humanoid (elf)"
class:
 - "Rahadin"
subClass:
 - "CR 10"
cover: "Rahadin.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/10
  - source/cos
---
###### Rahadin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Curse of Strahd
___

> [!infobox|no-t right]
> ![[Rahadin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (studded leather) |
> | :FasHeart: HP | 135 (18d8 + 54) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Curse of Strahd |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 22 | 17 | 15 | 16 | 18 |
| **Mod** | +2 | +6 | +3 | +2 | +3 | +4 |

**Speed:** 35 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 21
**Languages:** Common, Elvish
**Saving Throws:** Con +7, Wis +7
**Skills:** Deception +8, Insight +7, Intimidation +12, Perception +11, Stealth +14

---

### Traits

**Deathly Choir.** Any creature within 10 feet of Rahadin that isn't protected by a mind blank spell hears in its mind the screams of the thousands of people Rahadin has killed. As a bonus action, Rahadin can force all creatures that can hear the screams to make a DC 16 Wisdom saving throw. Each creature takes 16 (3d10) psychic damage on a failed save, or half as much damage on a successful one.

**Fey Ancestry.** Rahadin has advantage on saving throws against being charmed, and magic can't put him to sleep.

**Mask of the Wild.** Rahadin can attempt to hide even when he is only lightly obscured by foliage, heavy rain, falling snow, mist, and other natural phenomena.


---

### Actions

**Multiattack.** Rahadin attacks three times with his scimitar, or twice with his poisoned darts.

**Scimitar.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 9 (1d6 + 6) slashing damage.

**Poisoned Dart.** Ranged Weapon Attack: +10 to hit, range 20/60 ft., one target. *Hit:* 8 (1d4 + 6) piercing damage plus 5 (2d4) poison damage.


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