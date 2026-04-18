---
type: pc
race: "Monstrosity (lycanthrope)"
class:
 - "Werebear"
subClass:
 - "CR 5"
cover: "Werebear.png"
campaign:
locations:
tags:
  - race/lycanthrope
  - affinity/hostile
  - type/monstrosity
  - size/small
  - cr/5
  - source/xmm
---
###### Werebear
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Werebear.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Small Monstrosity (lycanthrope) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 135 (18d8 + 54) |
> | :FasUserGroup: Race | Monstrosity (lycanthrope) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 17 | 11 | 12 | 12 |
| **Mod** | +4 | +0 | +3 | +0 | +1 | +1 |

**Speed:** 30 ft., climb 30 ft. ((bear form only)) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 17
**Languages:** Common (can't speak in bear form)
**Skills:** Perception +7

---

### Actions

**Multiattack.** The werebear makes two attacks, using Handaxe or Rend in any combination. It can replace one attack with a Bite attack.

**Bite (Bear or Hybrid Form Only).** m +7, reach 5 ft. *Hit:* 17 (2d12 + 4) Piercing damage. If the target is a Humanoid, it is subjected to the following effect. con DC 14.  The target is cursed. If the cursed target drops to 0 Hit Points, it instead becomes a Werebear under the DM's control and has 10 Hit Points.  The target is immune to this werebear's curse for 24 hours.

**Handaxe (Humanoid or Hybrid Form Only).** m,r +7, reach 5 ft or range 20/60 ft. *Hit:* 14 (3d6 + 4) Slashing damage.

**Rend (Bear or Hybrid Form Only).** m +7, reach 5 ft. *Hit:* 13 (2d8 + 4) Slashing damage.


---

### Bonus Actions

**Shape-Shift.** The werebear shape-shifts into a Large bear-humanoid hybrid form or a Large bear, or it returns to its true humanoid form. Its game statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed.


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