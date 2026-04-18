---
type: pc
race: "Undead"
class:
 - "Vampirate Mage"
subClass:
 - "CR 5"
cover: "Vampirate Mage.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/5
  - source/bam
---
###### Vampirate Mage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Vampirate Mage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 68 (8d8 + 32) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 18 | 13 | 14 | 15 |
| **Mod** | +1 | +2 | +4 | +1 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** the languages it knew in life
**Saving Throws:** Wis +5, Cha +5
**Damage Vulnerabilities:** radiant
**Damage Immunities:** cold; necrotic; poison
**Condition Immunities:** charmed; exhaustion; poisoned

---

### Traits

**Explode.** When the mage is reduced to 0 hit points, it explodes in a cloud of ash. Any creature within 5 feet of it must succeed on a DC 14 Constitution saving throw or take 11 (2d10) necrotic damage.

**Spider Climb.** The mage can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Unusual Nature.** The mage doesn't require air or drink.


---

### Actions

**Multiattack.** The mage makes two Ray of Cold attacks.

**Energy Drain.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 30 ft., one creature. *Hit:* 22 (4d10) necrotic damage. A Humanoid reduced to 0 hit points by this attack dies and instantly transforms into a free-willed shadow under the DM's control.

**Ray of Cold.** Ranged Spell Attack: +5 to hit, range 120 ft., one target. *Hit:* 11 (2d8 + 2) cold damage.


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