---
type: pc
race: "Humanoid (tabaxi)"
class:
 - "Tabaxi Minstrel"
subClass:
 - "CR 1/4"
cover: "Tabaxi Minstrel.png"
campaign:
locations:
tags:
  - race/tabaxi
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-4
  - source/toa
---
###### Tabaxi Minstrel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Tabaxi Minstrel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Humanoid (tabaxi) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Humanoid (tabaxi) |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 11 | 14 | 12 | 16 |
| **Mod** | +0 | +2 | +0 | +2 | +1 | +3 |

**Speed:** 30 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common plus any two languages
**Skills:** Perception +3, Performance +7, Persuasion +5, Stealth +4

---

### Traits

**Feline Agility.** When the tabaxi moves on its turn in combat, it can double its speed until the end of the turn. Once it uses this ability, the tabaxi can't use it again until it moves 0 feet on one of its turns.

**Inspire (1/Day).** While taking a short rest, the tabaxi can spend 1 minute singing, playing an instrument, telling a story, or reciting a poem to soothe and inspire creatures other than itself. Up to five creatures of the tabaxi's choice that can see and hear its performance gain 8 temporary hit points at the end of the tabaxi's short rest.


---

### Actions

**Multiattack.** The tabaxi makes two claws attacks or two dart attacks.

**Claws.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4) slashing damage.

**Dart.** Ranged Weapon Attack: +4 to hit, range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


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