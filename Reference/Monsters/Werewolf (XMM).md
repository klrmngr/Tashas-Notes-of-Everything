---
type: pc
race: "Monstrosity (lycanthrope)"
class:
 - "Werewolf"
subClass:
 - "CR 3"
cover: "Werewolf.png"
campaign:
locations:
tags:
  - race/lycanthrope
  - affinity/hostile
  - type/monstrosity
  - size/small
  - cr/3
  - source/xmm
---
###### Werewolf
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Werewolf.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Monstrosity (lycanthrope) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 71 (11d8 + 22) |
> | :FasUserGroup: Race | Monstrosity (lycanthrope) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 14 | 10 | 11 | 10 |
| **Mod** | +3 | +2 | +2 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 14
**Languages:** Common (can't speak in wolf form)
**Skills:** Perception +4, Stealth +4

---

### Traits

**Pack Tactics.** The werewolf has Advantage on an attack roll against a creature if at least one of the werewolf's allies is within 5 feet of the creature and the ally doesn't have the Incapacitated condition.


---

### Actions

**Multiattack.** The werewolf makes two attacks, using Scratch or Longbow in any combination. It can replace one attack with a Bite attack.

**Bite (Wolf or Hybrid Form Only).** m +5, reach 5 ft. *Hit:* 12 (2d8 + 3) Piercing damage. If the target is a Humanoid, it is subjected to the following effect. con DC 12.  The target is cursed. If the cursed target drops to 0 Hit Points, it instead becomes a Werewolf under the DM's control and has 10 Hit Points.  The target is immune to this werewolf's curse for 24 hours.

**Scratch.** m +5, reach 5 ft. *Hit:* 10 (2d6 + 3) Slashing damage.

**Longbow (Humanoid or Hybrid Form Only).** r +4, range 150/600 ft. *Hit:* 11 (2d8 + 2) Piercing damage.


---

### Bonus Actions

**Shape-Shift.** The werewolf shape-shifts into a Large wolf-humanoid hybrid or a Medium wolf, or it returns to its true humanoid form. Its game statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed.


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