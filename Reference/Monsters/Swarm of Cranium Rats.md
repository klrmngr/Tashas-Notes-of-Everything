---
type: pc
race: "Swarm of Tiny Aberrations"
class:
 - "Swarm of Cranium Rats"
subClass:
 - "CR 5"
cover: "Swarm of Cranium Rats.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/5
  - source/mpmm
---
###### Swarm of Cranium Rats
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Swarm of Cranium Rats.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Aberrations |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 76 (17d8) |
> | :FasUserGroup: Race | Swarm of Tiny Aberrations |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 10 | 15 | 11 | 14 |
| **Mod** | -1 | +2 | +0 | +2 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., passive Perception 10
**Languages:** telepathy 30 ft.
**Damage Resistances:** bludgeoning; piercing; slashing
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; prone; restrained; stunned

---

### Traits

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny rat. The swarm can't regain hit points or gain temporary hit points.

**Telepathic Shroud.** The swarm is immune to any effect that would sense its emotions or read its thoughts, as well as to all divination spells.


---

### Actions

**Bites.** Melee Weapon Attack: +5 to hit, reach 0 ft., one target in the swarm's space. *Hit:* 14 (4d6) piercing damage, or 7 (2d6) piercing damage if the swarm has half of its hit points or fewer, plus 22 (5d8) psychic damage.


---

### Bonus Actions

**Illumination.** The swarm sheds dim light from its brains in a 5-foot radius, increases the illumination to bright light in a 5- to 20-foot radius (and dim light for an additional number of feet equal to the chosen radius), or extinguishes the light.


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