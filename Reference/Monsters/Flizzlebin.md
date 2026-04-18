---
type: pc
race: "Humanoid (gnome)"
class:
 - "Flizzlebin"
subClass:
 - "CR 1"
cover: "Flizzlebin.png"
campaign:
locations:
tags:
  - race/gnome
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1
  - source/wtthc
---
###### Flizzlebin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WttHC
___

> [!infobox|no-t right]
> ![[Flizzlebin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Humanoid (gnome) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 38 (7d6 + 14) |
> | :FasUserGroup: Race | Humanoid (gnome) |
> | :FasBook: Source | WttHC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 15 | 16 | 10 | 12 |
| **Mod** | -1 | +2 | +2 | +3 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Common, Dwarvish, Gnomish
**Skills:** Arcana +5, Stealth +4

---

### Traits

**Magic Resistance.** Flizzlebin has Advantage on saving throws against spells and other magical effects.

**Ventriloquist.** Flizzlebin can project his voice from anywhere within 1 mile of himself.


---

### Actions

**Dazzling Confetti.** m,r +5, reach 5 ft. or range 60 ft. *Hit:* 10 (2d6 + 3) Radiant damage.

**Vanishing Trick (3/Day).** Flizzlebin has the Invisible condition for 10 minutes. This effect ends early immediately after Flizzlebin makes an attack roll, deals damage, or has the Incapacitated condition, or if his hat is removed.


---

### Reactions

**Distracting Glitter.**  Flizzlebin is hit by an attack roll.  Flizzlebin adds 2 to his AC against that attack, possibly causing it to miss.


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