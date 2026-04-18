---
type: pc
race: "Humanoid (half-elf)"
class:
 - "Jaheira"
subClass:
 - "CR 13"
cover: "Jaheira.png"
campaign:
locations:
tags:
  - race/half-elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/13
  - source/mabjov
---
###### Jaheira
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Jaheira.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (half-elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 11; 16 with barkskin |
> | :FasHeart: HP | 150 (20d8 + 60) |
> | :FasUserGroup: Race | Humanoid (half-elf) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 12 | 16 | 12 | 20 | 15 |
| **Mod** | +2 | +1 | +3 | +1 | +5 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 20
**Languages:** Common, Druidic, Elvish, Sylvan
**Saving Throws:** Con +8, Wis +10
**Skills:** Medicine +10, Nature +6, Perception +10

---

### Traits

**Fey Ancestry.** Jaheira has advantage on saving throws against being charmed, and magic can't put Jaheira to sleep.


---

### Actions

**Multiattack.** Jaheira makes three Quarterstaff attacks.

**Quarterstaff.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 5 (1d8 + 5) bludgeoning damage plus 21 (6d6) thunder damage.

**Cleansing Plague (Recharge 6).** Jaheira targets a creature she can see within 60 feet and causes a swarm of flying insects to cover the creature. The creature must make a DC 18 Constitution saving throw, taking 44 (8d10) piercing damage on a failed save, or half as much damage on a successful one. If the target fails their saving throw they are also blinded until the end of their next turn.


---

### Bonus Actions

**Mighty Summons (1/Day).** Jaheira summons three CR 2 Beasts or six CR 1 Beasts. These summoned creatures have maximum hit points and the damage they inflict is considered magical for the purpose of overcoming immunity and resistance to nonmagical attacks and damage.


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