---
type: pc
race: "Undead"
class:
 - "Vampirate Captain"
subClass:
 - "CR 6"
cover: "Vampirate Captain.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/6
  - source/bam
---
###### Vampirate Captain
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Vampirate Captain.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 85 (10d8 + 40) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 16 | 18 | 12 | 13 | 16 |
| **Mod** | +2 | +3 | +4 | +1 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** the languages it knew in life
**Saving Throws:** Con +7, Wis +4, Cha +6
**Damage Vulnerabilities:** radiant
**Damage Immunities:** cold; necrotic; poison
**Condition Immunities:** charmed; exhaustion; poisoned

---

### Traits

**Explode.** When the captain is reduced to 0 hit points, it explodes in a cloud of ash. Any creature within 5 feet of it must succeed on a DC 15 Constitution saving throw or take 16 (3d10) necrotic damage.

**Spider Climb.** The captain can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Unusual Nature.** The captain doesn't require air or drink.


---

### Actions

**Energy Drain.** Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 30 ft., one creature. *Hit:* 22 (4d10) necrotic damage. A Humanoid reduced to 0 hit points by this attack dies and instantly transforms into a free-willed shadow or vampirate (captain's choice) under the DM's control.

**Heavy Crossbow.** Ranged Weapon Attack: +6 to hit, range 100/400 ft., one target. *Hit:* 19 (3d10 + 3) piercing damage.

**Ship Invisibility (Recharges after a Short or Long Rest).** A ship upon which the captain stands, along with all creatures and objects aboard it, becomes invisible to creatures not aboard the ship. The captain must concentrate on this magical effect to maintain it (as if concentrating on a spell), and it lasts for up to 1 hour. The effect ends if the captain leaves the ship.


---

### Reactions

**Uncanny Dodge.** The captain halves the damage that it takes from an attack that hits it. The captain must be able to see the attacker.


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