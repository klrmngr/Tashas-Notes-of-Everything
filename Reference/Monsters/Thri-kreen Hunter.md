---
type: pc
race: "Monstrosity"
class:
 - "Thri-kreen Hunter"
subClass:
 - "CR 2"
cover: "Thri-kreen Hunter.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/2
  - source/bam
---
###### Thri-kreen Hunter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Thri-kreen Hunter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 60 (11d8 + 11) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 16 | 13 | 10 | 14 | 9 |
| **Mod** | +2 | +3 | +1 | +0 | +2 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** telepathy 60 ft., Thri-kreen
**Skills:** Perception +4, Stealth +5, Survival +6

---

### Actions

**Multiattack.** The thri-kreen makes two Gythka or Chatkcha attacks.

**Gythka.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) slashing damage.

**Chatkcha.** Ranged Weapon Attack: +5 to hit, range 30/120 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.


---

### Bonus Actions

**Chameleon Carapace.** The thri-kreen changes the color of its carapace to match the color and texture of its surroundings, gaining advantage on Dexterity (Stealth) checks it makes to hide in those surroundings.

**Leap.** The thri-kreen leaps up to 20 feet in any direction, provided its speed isn't 0.


---

### Reactions

**Parry.** The thri-kreen adds 2 to its AC against one melee attack that would hit it. To do so, the thri-kreen must see the attacker and be wielding a melee weapon.


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