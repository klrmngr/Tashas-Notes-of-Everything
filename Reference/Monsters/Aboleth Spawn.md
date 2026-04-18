---
type: pc
race: "Aberration"
class:
 - "Aboleth Spawn"
subClass:
 - "CR 5"
cover: "Aboleth Spawn.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/5
  - source/crcotn
---
###### Aboleth Spawn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Aboleth Spawn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 93 (11d8 + 44) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 11 | 18 | 7 | 12 | 9 |
| **Mod** | +4 | +0 | +4 | -2 | +1 | -1 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** Common, Deep Speech, telepathy 60 ft.
**Skills:** Perception +4
**Damage Resistances:** psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Abolethic Vessel.** The spawn must obey its aboleth master.

**Amphibious.** The spawn can breathe air and water.

**Water Dependency.** The spawn takes 6 (1d12) acid damage every 10 minutes it goes without being immersed in water.


---

### Actions

**Multiattack.** The spawn makes one Spear attack, two Tentacle attacks, and one Psychic Lash attack.

**Spear.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage, or 8 (1d8 + 4) piercing damage when used with two hands to make a melee attack.

**Tentacle.** Melee Weapon Attack: +7 to hit, reach 10 ft., one creature. *Hit:* The target is grappled (escape DC 14) and takes 9 (2d8) psychic damage at the start of each of its turns until the grapple ends. The spawn has four tentacles, each of which can grapple one creature.

**Psychic Lash.** Ranged Spell Attack: +7 to hit, range 120 ft., one creature. *Hit:* 18 (4d8) psychic damage.


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