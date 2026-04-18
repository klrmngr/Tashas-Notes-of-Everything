---
type: pc
race: "Dragon (lycanthrope)"
class:
 - "Werewyvern"
subClass:
 - "CR 8"
cover: "Werewyvern.png"
campaign:
locations:
tags:
  - race/lycanthrope
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/8
  - source/fraif
---
###### Werewyvern
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Werewyvern.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Dragon (lycanthrope) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 152 (16d8 + 80) |
> | :FasUserGroup: Race | Dragon (lycanthrope) |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 15 | 20 | 10 | 12 | 12 |
| **Mod** | +4 | +2 | +5 | +0 | +1 | +1 |

**Speed:** 30 ft., fly 40 ft. ((wyvern or hybrid form only)) &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 14
**Languages:** Common, Draconic (can't speak in wyvern form)
**Saving Throws:** Dex +5, Wis +4
**Skills:** Perception +4, Stealth +5

---

### Traits

**Flyby (Wyvern or Hybrid Form Only).** The werewyvern doesn't provoke an Opportunity Attack action when it flies out of an enemy's reach.


---

### Actions

**Multiattack.** The werewyvern makes three attacks, using Javelin or Rend in any combination. It can replace one of these attacks with one Stinger attack.

**Javelin (Humanoid or Hybrid Form Only).** m,r +7, reach 5 ft. or range 30/120 ft. *Hit:* 18 (4d6 + 4) Piercing damage.

**Rend.** m +7, reach 5 ft. *Hit:* 18 (4d6 + 4) Slashing damage.

**Stinger (Wyvern or Hybrid Form Only).** m +7, reach 5 ft. *Hit:* 7 (1d6 + 4) Piercing damage plus 16 (3d10) Poison damage, and the target has the Poisoned condition until the start of the werewyvern's next turn. If the target is a Humanoid, it is subjected to the following effect. con DC 16.  The target is cursed. If the cursed target drops to 0 Hit Points, it instead becomes a Werewyvern under the DM's control and has 20 Hit Points.  The target is immune to this werewyvern's curse for 24 hours.


---

### Bonus Actions

**Shape-Shift.** The werewyvern shape-shifts into a Medium wyvern-humanoid hybrid or a Large wyvern, or it returns to its true humanoid form. Its game statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed.


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