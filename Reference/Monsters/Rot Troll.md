---
type: pc
race: "Giant"
class:
 - "Rot Troll"
subClass:
 - "CR 9"
cover: "Rot Troll.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/large
  - cr/9
  - source/mpmm
---
###### Rot Troll
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Rot Troll.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Giant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 138 (12d10 + 72) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 22 | 5 | 8 | 4 |
| **Mod** | +4 | +1 | +6 | -3 | -1 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Giant
**Skills:** Perception +3
**Damage Immunities:** necrotic

---

### Traits

**Rancid Degeneration.** At the end of each of the troll's turns, each creature within 5 feet of it takes 11 (2d10) necrotic damage, unless the troll has taken acid or fire damage since the end of its last turn.


---

### Actions

**Multiattack.** The troll makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage plus 16 (3d10) necrotic damage.

**Claws.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage plus 7 (2d6) necrotic damage.


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