---
type: pc
race: "Monstrosity"
class:
 - "Xvart Warlock of Raxivort"
subClass:
 - "CR 1"
cover: "Xvart Warlock of Raxivort.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/small
  - cr/1
  - source/mpmm
---
###### Xvart Warlock of Raxivort
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Xvart Warlock of Raxivort.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Monstrosity |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 22 (5d6 + 5) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 12 | 8 | 11 | 12 |
| **Mod** | -1 | +2 | +1 | -1 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., passive Perception 10
**Languages:** Abyssal
**Skills:** Stealth +3

---

### Traits

**Raxivort's Blessing.** When the xvart reduces an enemy to 0 hit points, the xvart gains 4 temporary hit points.

**Raxivort's Tongue.** The xvart can communicate with ordinary [[Bat|bats]] and [[Rat|rats]], as well as [[Giant Bat|giant bats]] and [[Giant Rat|giant rats]].


---

### Actions

**Multiattack.** The xvart makes two Scimitar or Raxivort's Bite attacks.

**Scimitar.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) slashing damage.

**Raxivort's Bite.** Ranged Spell Attack: +3 to hit, range 30 ft., one creature. *Hit:* 7 (1d10 + 2) poison damage.


---

### Bonus Actions

**Low Cunning.** The xvart takes the Disengage action.


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