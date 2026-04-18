---
type: pc
race: "Monstrosity (lycanthrope)"
class:
 - "Weretiger"
subClass:
 - "CR 4"
cover: "Weretiger.png"
campaign:
locations:
tags:
  - race/lycanthrope
  - affinity/hostile
  - type/monstrosity
  - size/small
  - cr/4
  - source/xmm
---
###### Weretiger
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Weretiger.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Monstrosity (lycanthrope) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 120 (16d8 + 48) |
> | :FasUserGroup: Race | Monstrosity (lycanthrope) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 15 | 16 | 10 | 13 | 11 |
| **Mod** | +3 | +2 | +3 | +0 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 15
**Languages:** Common (can't speak in tiger form)
**Skills:** Perception +5, Stealth +4

---

### Actions

**Multiattack.** The weretiger makes two attacks, using Scratch or Longbow in any combination. It can replace one attack with a Bite attack.

**Bite (Tiger or Hybrid Form Only).** m +5, reach 5 ft. *Hit:* 12 (2d8 + 3) Piercing damage. If the target is a Humanoid, it is subjected to the following effect. con DC 13.  The target is cursed. If the cursed target drops to 0 Hit Points, it instead becomes a Weretiger under the DM's control and has 10 Hit Points.  The target is immune to this weretiger's curse for 24 hours.

**Scratch.** m +5, reach 5 ft. *Hit:* 10 (2d6 + 3) Slashing damage.

**Longbow (Humanoid or Hybrid Form Only).** r +4, range 150/600 ft. *Hit:* 11 (2d8 + 2) Piercing damage.


---

### Bonus Actions

**Prowl (Tiger or Hybrid Form Only).** The weretiger moves up to its Speed without provoking Opportunity Attacks. At the end of this movement, the weretiger can take the Hide action.

**Shape-Shift.** The weretiger shape-shifts into a Large tiger-humanoid hybrid or a Large tiger, or it returns to its true humanoid form. Its game statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed.


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