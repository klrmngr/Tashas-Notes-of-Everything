---
type: pc
race: "Monstrosity (lycanthrope)"
class:
 - "Wererat"
subClass:
 - "CR 2"
cover: "Wererat.png"
campaign:
locations:
tags:
  - race/lycanthrope
  - affinity/hostile
  - type/monstrosity
  - size/small
  - cr/2
  - source/xmm
---
###### Wererat
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Wererat.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Monstrosity (lycanthrope) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 60 (11d8 + 11) |
> | :FasUserGroup: Race | Monstrosity (lycanthrope) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 12 | 11 | 10 | 8 |
| **Mod** | +0 | +3 | +1 | +0 | +0 | -1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 14
**Languages:** Common (can't speak in rat form)
**Skills:** Perception +4, Stealth +5

---

### Actions

**Multiattack.** The wererat makes two attacks, using Scratch or Hand Crossbow in any combination. It can replace one attack with a Bite attack.

**Bite (Rat or Hybrid Form Only).** m +5, reach 5 ft. *Hit:* 8 (2d4 + 3) Piercing damage. If the target is a Humanoid, it is subjected to the following effect. con DC 11.  The target is cursed. If the cursed target drops to 0 Hit Points, it instead becomes a Wererat under the DM's control and has 10 Hit Points.  The target is immune to this wererat's curse for 24 hours.

**Scratch.** m +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Slashing damage.

**Hand Crossbow (Humanoid or Hybrid Form Only).** r +5, range 30/120 ft. *Hit:* 6 (1d6 + 3) Piercing damage.


---

### Bonus Actions

**Shape-Shift.** The wererat shape-shifts into a Medium rat-humanoid hybrid or a Small rat, or it returns to its true humanoid form. Its game statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed.


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