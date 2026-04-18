---
type: pc
race: "Monstrosity"
class:
 - "Thri-kreen Gladiator"
subClass:
 - "CR 7"
cover: "Thri-kreen Gladiator.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/7
  - source/bam
---
###### Thri-kreen Gladiator
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Thri-kreen Gladiator.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 142 (19d8 + 57) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 18 | 16 | 10 | 15 | 11 |
| **Mod** | +4 | +4 | +3 | +0 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** telepathy 60 ft., Thri-kreen
**Saving Throws:** Str +7, Dex +7, Wis +5
**Skills:** Acrobatics +7, Athletics +7, Perception +5
**Condition Immunities:** frightened

---

### Actions

**Multiattack.** The thri-kreen makes two Gythka attacks and one Chatkcha attack.

**Gythka.** Melee Weapon Attack: +7 to hit (with advantage if the thri-kreen is missing any hit points), reach 5 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage.

**Chatkcha.** Ranged Weapon Attack: +7 to hit (with advantage if the thri-kreen is missing any hit points), range 30/120 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage.


---

### Bonus Actions

**Leap.** The thri-kreen leaps up to 20 feet in any direction, provided its speed isn't 0.


---

### Reactions

**Parry.** The thri-kreen adds 3 to its AC against one melee attack that would hit it. To do so, the thri-kreen must see the attacker and be wielding a melee weapon.


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