---
type: pc
race: "Construct"
class:
 - "Baba Lysaga's Creeping Hut"
subClass:
 - "CR 11"
cover: "Baba Lysaga's Creeping Hut.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/gargantuan
  - cr/11
  - source/cos
---
###### Baba Lysaga's Creeping Hut
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Curse of Strahd
___

> [!infobox|no-t right]
> ![[Baba Lysaga's Creeping Hut.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Gargantuan Construct |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 263 (17d20 + 85) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Curse of Strahd |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 7 | 20 | 1 | 3 | 3 |
| **Mod** | +8 | -2 | +5 | -5 | -4 | -4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft. (blind beyond this radius), passive Perception 6
**Languages:** —
**Saving Throws:** Con +9, Wis +0, Cha +0
**Damage Immunities:** poison; psychic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; prone

---

### Traits

**Constructed Nature.** An animated object doesn't require air, food, drink, or sleep.
The magic that animates an object is dispelled when the construct drops to 0 hit points. An animated object reduced to 0 hit points becomes inanimate and is too damaged to be of much use or value to anyone.

**Antimagic Susceptibility.** The hut is incapacitated while the magic gem that animates it is in the area of an antimagic field. If targeted by dispel magic, the hut must succeed on a Constitution saving throw against the caster's spell save DC or fall unconscious for 1 minute.

**Siege Monster.** The hut deals double damage to objects and structures.


---

### Actions

**Multiattack.** The hut makes three attacks with its roots. It can replace one of these attacks with a rock attack.

**Root.** Melee Weapon Attack: +12 to hit, reach 60 ft., one target. *Hit:* 30 (4d10 + 8) bludgeoning damage.

**Rock.** Ranged Weapon Attack: +12 to hit, range 120 ft., one target. *Hit:* 21 (3d8 + 8) bludgeoning damage.


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