---
type: pc
race: "Undead"
class:
 - "Vampirate"
subClass:
 - "CR 2"
cover: "Vampirate.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/2
  - source/bam
---
###### Vampirate
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Vampirate.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 42 (5d8 + 20) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 18 | 10 | 11 | 12 |
| **Mod** | +1 | +2 | +4 | +0 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** the languages it knew in life
**Damage Vulnerabilities:** radiant
**Damage Immunities:** cold; necrotic; poison
**Condition Immunities:** charmed; exhaustion; poisoned

---

### Traits

**Explode.** When the vampirate is reduced to 0 hit points, it explodes in a cloud of ash. Any creature within 5 feet of it must succeed on a DC 14 Constitution saving throw or take 5 (1d10) necrotic damage.

**Spider Climb.** The vampirate can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Unusual Nature.** The vampirate doesn't require air or drink.


---

### Actions

**Energy Drain.** Melee or Ranged Spell Attack: +4 to hit, reach 5 ft. or range 30 ft., one creature. *Hit:* 11 (2d10) necrotic damage. A Humanoid reduced to 0 hit points by this attack dies and instantly transforms into a free-willed shadow under the DM's control.

**Light Crossbow.** Ranged Weapon Attack: +4 to hit, range 80/320 ft., one target. *Hit:* 11 (2d8 + 2) piercing damage.


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